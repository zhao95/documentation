# Contributing to Vapor Docs



let package = Package(
    name: "MyApp",
    dependencies: [
        .Package(url: "https://github.com/vapor/vapor.git", majorVersion: 1, minor: 0),
        .Package(url: "https://github.com/vapor/mysql-provider.git", majorVersion: 1, minor: 0)
    ]
)
It's important to vapor clean or vapor build --clean after adding new packages.



I found running`vapor clean`, an error will be reported later, missing dependencies, this attempt to use ``vapor build``, there is no mistake.


But add this  ` .Package(url: "https://github.com/vapor/mysql-provider.git", majorVersion: 1, minor: 0)`
problems arising from the lack of how to solve other dependencies.?

Of course, I do not understand English... ...

