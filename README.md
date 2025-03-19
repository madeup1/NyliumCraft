# NyliumCraft

NyliumCraft is a Minecraft 1.8.9 customizable server software made entirely in Go focusing on library use.

## Plan

The plan for NyliumCraft is to change the future of how minecraft server softwares work, trying to switch over from Java to other languages, and inspire people to follow suit. By no means am I a professional developer, I am a highschooler with only a few years of part-time coding experience, so don't expect this to be the perfectly coded or structured repository.

## Structure/Design

The structure of NyliumCraft is to be primarily based upon interfaces so that everything can be highly modular. The idea behind this is to allow the users to create almost anything imaginable. Also, with performance being a high priority, code will be heavily looked over for ways to be optimized or run faster at all times.

## Installing

To install Nylium, use Go's package manager.

```bash
go install github.com/madeup1/NyliumCraft
```

## Usage

As NyliumCraft is a dynamic server, there is a little more you have to do than just start the server.

For example, you must supply a Client Factory, and return a Client that matches the Client interface.

```go
insert code here
```

## Contributing

Pull request are welcomed but may take a while to be implemented. Please open an issue first, as I will take a crack at the problem or issue first.

Please understand, this is a project maintained by a single highschooler, do not expect this to be similarily maintained as other server softwares, primarily those in Java.

## License

[MIT](https://choosealicense.com/licenses/mit/)