# mkp5
Initialize a [p5.js](https://p5js.org/) project from the command line! 🐦

This script creates all the necessary files for a `p5.js` project, including an `index.html`, `sketch.js`, and `style.css` file. You can choose a directory to create the `p5` project in (default: current directory, aka `.`), and the name of the sketch (default: `sketch`).

## Installation and Usage

ℹ️This assumes you are running Linux or Windows Subsystem for Linux (WSL).

1. `git clone` this repository, or download the `mkp5` file directly.

2. Make the file executable:

```bash
chmod +x the/path/to/mkp5
```

3. (Optional): Add the file to your PATH. For example, when using bash:

```bash
echo "export PATH=\$PATH:/the/path/to/mkp5" >> ~/.bashrc
```

Don't forget source your `.bashrc` (or simply restart your terminal).

```bash
source ~/.bashrc
```

4. If you completed step 3, you can now run `mkp5` from anywhere! 
```bash
mkp5 [directory] [sketch name]
```

If you didn't complete step 3, you can run the script like this:

```bash
/the/path/to/mkp5 [directory] [sketch name]
```

(Note that if you did not complete step 3, and are trying to run `mkp5` from the current directory, you'll have to prepend `./` to the script name.)

```bash
./mkp5 [directory] [sketch name]
```

## Examples

```bash
mkp5
```

```bash
mkp5 my-p5-project
```

```bash
mkp5 my-p5-project my-sketch
```

## Contributing

Feel free to fork this repository and submit a PR if you have any improvements, features or bug fixes!
