# React Production Build PSA

The [React Developer Tools](https://github.com/facebook/react-devtools)
extension displays an icon indicating if the current website is running a
development, production, or out of date build of React:

![dev message](https://reactjs.org/static/devtools-dev-e434ce2f7e64f63e597edf03f4465694-1e9b4.png)
---
![prod message](https://reactjs.org/static/devtools-prod-d0f767f80866431ccdec18f200ca58f1-1e9b4.png)

Websites should [use the production
build](https://reactjs.org/docs/optimizing-performance.html#use-the-production-build)
to reduce the build size and improve runtime performance. The production build
excludes warning messages that are helpful during development. Turning on
production mode can also help if other packages contain development-specific
code.

These are websites that I have noticed using the development build in
production. The intention is **not** to shame them. Using the development build
in production is an easy thing to overlook since the website will still
function without obvious issues. Rather, the goals are to 1) increase awareness
of the production build and 2) hopefully get the attention of the developers
behind these websites so that they can make the change.

* [account.ubisoft.com](https://account.ubisoft.com/)
* [allmychanges.com](https://allmychanges.com/)
* [clearbit.com](https://clearbit.com/)
* [fortawesome.com](https://fortawesome.com/)
* [hbr.org](https://hbr.org/)
* [indiewire.com](https://www.indiewire.com/)
* [indochino.com](https://www.indochino.com/)
* [streeteasy.com](https://streeteasy.com/)
* [technologyreview.com](https://www.technologyreview.com/)
* [terminal.sexy](https://terminal.sexy/)
* [typography.com](https://www.typography.com/)
* [variety.com](https://variety.com/)
* [visible.com](https://www.visible.com/)

## Contributing

Create pull requests to add or remove entries from the list. I try to contact
the websites to let them know about the issue. If you're adding one, let me
know if you have already tried to contact them or if you would like me to do
so.

Please do not create a pull request if the website is using an out of date
build. Turning on the production build *should* be an easy and safe change, but
upgrading React might involve much more significant changes, depending on the
code base. Developers also probably already know that React releases new
versions regularly.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
