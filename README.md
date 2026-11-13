# Smart Home Thermostat

A smart-home thermostat dashboard: a circular temperature dial you drag, monitoring cards, an animated energy usage chart and bottom navigation.

## Built with

- Uno Platform single project, `Uno.Sdk` 6.7.30 (pinned in `global.json`).
- Targets: Android, Desktop (net10.0).
- Material theme, Hosting and dependency injection, Uno Toolkit, MVVM (CommunityToolkit), Kiota HTTP client, Navigation extensions, Skia renderer.

## Run it

You need the .NET 10 SDK. Run `uno-check` first on a fresh machine.

```bash
dotnet run --project test/test.csproj -f net10.0-desktop
```

## Design docs

- [`SmartHomeDashboard_ProjectScope.md`](SmartHomeDashboard_ProjectScope.md)
- [`SMART_HOME_THERMOSTAT_IMPLEMENTATION.md`](SMART_HOME_THERMOSTAT_IMPLEMENTATION.md)

## License

MIT. See [LICENSE](LICENSE).
