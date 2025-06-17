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

```bash
dotnet new console -n DotnetConsoleApp
```

```bash
dotnet new console -n DotnetConsoleApp -f net8.0
```

```bash
dotnet new gitignore
```

```bash
dotnet new globaljson
```

### Run

```bash
dotnet run
```

```bash
dotnet watch run
```

## Docs

- [.NET 9.0 (Linux、macOS、Windows) のダウンロード | .NET](https://dotnet.microsoft.com/ja-jp/download/dotnet/9.0)
- [Introducing support for SLNX, a new, simpler solution file format in the .NET CLI - .NET Blog](https://devblogs.microsoft.com/dotnet/introducing-slnx-support-dotnet-cli/?hide_banner=true)
