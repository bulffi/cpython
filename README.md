# CPython Learning

## Env

I use Fedora 33 for my own dev env.

In order to use the debug function provided by VS Code, I choose to use the famous `Remote - Containers` plugin to do all the experiments inside of a container.

If you want to use this environment, you can just pull this repo, and open it in VS Code on any platform. VS Code will ask you whether you would like to open this in Docker, ang you'll click Yes.

I recommend using the following plugin inside of the container: 

- clangd (I use `bear` to generate the compile_commands.json file)
- cpptools (For breakpoints and inspecting local vars)

The corresponding `.vsix` file is also included in this repo so that you can install them for VS Code Server.