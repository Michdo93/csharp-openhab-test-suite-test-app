# csharp-openhab-test-suite test app

A single web page that runs the testers of
[csharp-openhab-test-suite](https://github.com/Michdo93/csharp-openhab-test-suite) 2.0.1 through the
[backend](https://github.com/Michdo93/csharp-openhab-test-suite-backend): ItemTester, ThingTester,
RuleTester, ChannelTester, PersistenceTester and SitemapTester with all their methods.

- `test…` methods with command, expected state and timeout; several accepted states are
  separated by `|` (`30|30.0`)
- types with dimension (`Number:Temperature`) for `checkItemIsType`
- result badge per method and the messages of the testers in the log

Open `index.html` in the browser (or via GitHub Pages), wake up the backend, enter the address
of openHAB and an API token (or myopenHAB e-mail and password) and connect. For a backend of
your own change `BACKEND` at the top of the script.

## License

MIT – see [LICENSE](LICENSE).
