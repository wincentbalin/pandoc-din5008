# Create DIN 5008 letters using Markdown

This template is an improvement of [Phoenix4815/pandoc_letter](https://github.com/Phoenix4815/pandoc_letter), with a couple of ideas from [selfawaresoup/latex-templates](https://github.com/selfawaresoup/latex-templates).

It does unterstand additional settings `invoice` and `frombank` now, to be able to write invoices.

There are two examples: a regular letter (in file [examples/brief1.md](examples/brief1.md)) and an invoice letter (in file [examples/brief1re.md](examples/brief1re.md), _re_ as in _Rechnung_), as well as the resulting PDF files.

You will find out about even more settings by studying the [Usage section in Phoenix4815/pandoc_letter](https://github.com/Phoenix4815/pandoc_letter#usage).

Also, in the directory `batch` there are some scripts you can use on Windows on daily basis. Execute `set_path.bat` to be able to execute other scripts, and simply run `mdltr file.md` for regular letters and `mdtblltr file.md` for invoice letters or any letters with tables (the Markdown table syntax as in [examples/brief1re.md](examples/brief1re.md)).

# Installation

As in [Usage section in Phoenix4815/pandoc_letter](https://github.com/Phoenix4815/pandoc_letter#usage).

# License

[Affero GPL 3.0](LICENSE)
