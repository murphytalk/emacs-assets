# Emacs Assets

To use in strict envrionment where GitLab and other public repositories are blocked.

## Prepare the assets in a free envrionment

```
7z a -xr"!.git" -xr"!*.elc" emacs2.doom.7z .doom.d .emacs.d
```

## Use assets

The path in the `el` files needs to be updated to refect the target environment.
