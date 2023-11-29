# text-2-slides
Experiment to create slides from text files.

## Experiment 1: Transform Markdown files to HTML

This experiment converts a markdown file to HTML using pandoc. Next, we will transform the HTML file into a slides deck.

### Requirements

* Install the latest version of [Pandoc](https://pandoc.org/).

### Considerations

* The input file for this experiment should be a markdown file that is located in the `scripts/assets/md-files` folder.
* The output file for this experiment will be placed in the `scripts/assets/html-files` folder.
* For the experiment purposes, we use as input a file named `what-is-marlowe.md`.
* To change the input file, you need to edit the script `md2html.sh` located in the `scripts` folder.

### Execution

1. Open a terminal window and navigate to the `scripts` folder.
2. To transform the MD file to HTML, execute the following command: `./md2html.sh`
3. After executing the command, you will se a new HTML file in the `scripts/assets/html-files` folder.

### Preliminary Conclusions

The conversion is straightforward, but it looks like a long way ahead to create the slide. We will try another approach.

## Experiment 2: Transform Markdown files to Power Point slides

This experiment uses pandoc to convert a Markdown file into Power Point slides (PPTX). This experiment is based on this blog post: [Producing Beamer slide shows from markdown using Pandoc](https://ashwinschronicles.github.io/beamer-slides-using-markdown-and-pandoc).

### Requirements

* Install the latest version of [Pandoc](https://pandoc.org/).

### Resources

* <https://ashwinschronicles.github.io/beamer-slides-using-markdown-and-pandoc>
* <https://pandoc.org/MANUAL.html#example-reveal.js>
* <https://pandoc.org/MANUAL.html#powerpoint-layout-choice>
* <https://stymied.medium.com/what-slides-from-markdown-5239ed31e7ac>
