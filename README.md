# ttctl
Binary releases of the TT CLI tool

## Install

```
curl -sSfL "https://raw.githubusercontent.com/greggyNapalm/ttctl/refs/heads/main/install-ttctl.sh" | bash
```

Install a specific version:
```
curl -sSfL "https://raw.githubusercontent.com/greggyNapalm/ttctl/refs/heads/main/install-ttctl.sh" | bash -s -- --version 1.0.0
```

Install to a custom directory:
```
curl -sSfL "https://raw.githubusercontent.com/greggyNapalm/ttctl/refs/heads/main/install-ttctl.sh" | bash -s -- --dir ~/.local/bin
```

## Usage

```
ttctl login --server-url https://your-tt-instance.example.com
ttctl teams list
ttctl monitors list --team <team-id>
ttctl monitors create --team <team-id> --name "Production API" --url "https://api.example.com/health"
```

Run `ttctl --help` for the full command reference.
