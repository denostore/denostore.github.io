# Deno Store

This is an online store for deno.

## Install

**With Python:**

```
curl -sSf https://raw.githubusercontent.com/denoland/deno_install/master/install.py | python
```

**With PowerShell:**

```powershell
iex (iwr https://raw.githubusercontent.com/denoland/deno_install/master/install.ps1)
```

_Note: Depending on your security settings, you may have to run
`Set-ExecutionPolicy RemoteSigned -Scope CurrentUser` first to allow downloaded
scripts to be executed._

Try it:

```
> deno http://deno.store/test.ts
```

See also [deno_install](https://github.com/denoland/deno_install).
