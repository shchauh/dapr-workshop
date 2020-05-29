For this workshop we need to install for prerequisites

[Install Docker] (#Install Docker)
[Install Dapr](#Install Dapr)
[Install .Net Core 3.1] (#Install .Net core 3.1)
[Install VS Code]



## Install Docker

[Install docker for your operating system](https://docs.docker.com/install/)

> For Windows user, ensure that `Docker Desktop For Windows` uses Linux containers.

## Install Dapr

**Windows**

Install the latest windows Dapr cli to `c:\dapr` and add this directory to User PATH environment variable.

```powershell
powershell -Command "iwr -useb https://raw.githubusercontent.com/dapr/cli/master/install/install.ps1 | iex"
```

**Linux**

Install the latest linux Dapr CLI to `/usr/local/bin`

```bash
wget -q https://raw.githubusercontent.com/dapr/cli/master/install/install.sh -O - | /bin/bash
```
**MacOS**

Install the latest darwin Dapr CLI to `/usr/local/bin`

```bash
curl -fsSL https://raw.githubusercontent.com/dapr/cli/master/install/install.sh | /bin/bash
```

Or install via [Homebrew](https://brew.sh)

```bash
brew install dapr/tap/dapr-cli
```

## Install .Net core 3.1

## Install Visual Studio Code
