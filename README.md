# DotnetConsoleApp
.NET Console App

## Ubuntu

### Check the Ubuntu version

```bash
lsb_release -ds
```

### Install

```bash
which dotnet
```

```bash
sudo apt update && \
sudo apt install -y dotnet-sdk-8.0
```

```bash
sudo add-apt-repository ppa:dotnet/backports && \
sudo apt update && \
sudo apt install -y dotnet-sdk-9.0
```

```bash
which dotnet
```

```bash
dotnet --version
```

```bash
dotnet --info
```

```bash
dotnet --list-sdks
```

### Template Instantiation

dotnet new console -n DotnetConsoleApp

dotnet new console -n DotnetConsoleApp -f net8.0

dotnet new gitignore

dotnet new globaljson

### Run

dotnet run

dotnet watch run
