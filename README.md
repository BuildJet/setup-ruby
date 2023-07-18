<div align="center">
    <img src="https://buildjet.com/buildjet-for-github-actions-logo2.svg" height="38">
</div>

---

This is a fork by [BuildJet for GitHub Actions](https://buildjet.com/for-github-actions).
It is **fully compatible with the official setup-ruby action**, simply replace `ruby/setup-ruby` with `buildjet/setup-ruby`.
Under the hood we simply switch the underlying caching package to our fully compatible `buildjet/cache`. No other changes have been made to this package.

For help migrating to BuildJet's setup-ruby, please visit our [migration guide](https://buildjet.com/for-github-actions/docs/guides/migrating-to-buildjet-cache).  
For detailed usage instructions, please visit the [official `ruby/setup-ruby` repository](https://github.com/ruby/setup-ruby).
