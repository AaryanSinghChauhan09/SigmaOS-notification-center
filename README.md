# SigmaOS notification-center-plugin

> Forked from AaryanSinghChauhan09/SigmaOS-notification-center-plugin (MIT). See `SIGMAOS_FORK.md`.

An optional bar widget for reviewing notifications handled by SigmaOS's
built-in notification service.

It adds:

- a Pending tab for unseen notifications;
- a Recently tab for notifications already shown;
- per-notification dismissal;
- Mark All as Seen and Clear Recent actions;
- a Do Not Disturb toggle.

The notification daemon, toast popups, history storage, DND state, and the
standard DND indicator remain part of SigmaOS itself. This plugin only provides
the bar popup for browsing that history.

## Install

```bash
sigmaos plugin add https://github.com/SigmaOS-io/sigmaos-notification-center-plugin.git --enable
```

The widget can be positioned explicitly:

```bash
sigmaos bar plugin move SigmaOS.notification-center --section right
```

## Development

Validate the manifest and entry point:

```bash
sigmaos plugin validate .
```

After changing plugin files:

```bash
sigmaos plugin rescan
sigmaos restart shell
```

## License

MIT
## Documentation

Wiki documentation is available in the SigmaOS Wiki Staging repository:

- [SigmaOS Wiki Staging](https://github.com/AaryanSinghChauhan09/sigmaos-wiki-staging#SigmaOS-notification-center) - Full Wiki documentation for all SigmaOS components

## See Also

Related SigmaOS **sigmaos** repositories:

- [SigmaOS-aether](../SigmaOS-aether/README.md) — SigmaOS-aether
- [SigmaOS-aether.nvim](../SigmaOS-aether.nvim/README.md) — SigmaOS-aether.nvim
- [SigmaOS-amiga-screensaver](../SigmaOS-amiga-screensaver/README.md) — SigmaOS-amiga-screensaver
- [SigmaOS-app-env](../SigmaOS-app-env/README.md) — SigmaOS-app-env
- [SigmaOS-archs](../SigmaOS-archs/README.md) — SigmaOS-archs
