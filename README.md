# text-2-slides
Experiment to create slides from text files.

## Experiment 1: Using Markdown files

This experiment converts a markdown file to HTML using pandoc. Next, we will transform the HTML file into a slides deck.

### Requirements

* Install the latest version of [Pandoc](https://pandoc.org/).

### Considerations

* The input file for this experiment should be a markdown file that is located in the `assets/md-files` folder.
* The output file for this experiment will be placed in the `assets/html-files` folder.
* For the experiment purposes, we use as input a file named `what-is-marlowe.md`.
* To change the input file, you need to edit the script `md2html.sh` located in the `scripts` folder.

### Execution

1. Open a terminal window and navigate to the `scripts` folder.
2. To transform the MD file to HTML, execute the following command: `./md2html.sh`
3. After executing the command, you will se a new HTML file in the `assets/html-files` folder.
