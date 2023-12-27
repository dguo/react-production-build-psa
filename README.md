# React Production Build PSA

The [React Developer Tools](https://github.com/facebook/react-devtools)
extension displays an icon indicating if the current website is running a
development, production, or out of date build of React.

Development:
![development icon](https://github.com/facebook/react/blob/main/packages/react-devtools-extensions/icons/128-development.png)

Production:
![production icon](https://github.com/facebook/react/blob/main/packages/react-devtools-extensions/icons/128-production.png)

Out of date:
![out of date
icon](https://github.com/facebook/react/blob/main/packages/react-devtools-extensions/icons/128-outdated.png)

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

* [crownshy.nyc](https://www.crownshy.nyc/)
* [deadline.com](https://deadline.com/)
* [fortawesome.com](https://fortawesome.com/)
* [hatsuhana.com](https://www.hatsuhana.com/)
* [hollywoodreporter.com](https://www.hollywoodreporter.com/)
* [indiewire.com](https://www.indiewire.com/)
* [rubirosanyc.com](https://www.rubirosanyc.com/)
* [terminal.sexy](https://terminal.sexy/)
* [variety.com](https://variety.com/)

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
