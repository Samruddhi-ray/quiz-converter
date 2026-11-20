# Quiz Converter for Canvas

Turn a question list from Word, Excel, CSV or plain text into a **QTI .zip** file that Canvas LMS imports as a ready-made quiz.

**Use it:** _link goes here after GitHub Pages is on_

## Why
Teachers often write quizzes in Word or Excel, then retype every question into Canvas one by one. This tool does the conversion in seconds.

## Private by design
- Runs entirely in your browser. Your questions are **never uploaded** anywhere.
- No sign-up, no cookies. The only thing counted is an anonymous page visit (via GoatCounter, if switched on); question text is never sent.
- The page's Content Security Policy (`connect-src 'none'`) blocks it from making any network request, so it *can't* send your data, even by accident.
- One HTML file with no outside libraries. You can read all the code, or save the page and use it offline.

## Supported question types
Multiple choice, multiple answers, true/false, short answer (fill in the blank) and essay, with points per question.

## Write questions like this
```
1. Which organ pumps blood? [2 pts]
a) Lungs
*b) Heart
c) Liver

2. What is the chemical symbol for water?
Answer: H2O | h2o
```
Put `*` before the correct option (in Word, you can make it **bold** instead). For Excel or CSV, download the template from the page.

## Import into Canvas
Course **Settings → Import Course Content → QTI .zip file** → choose the file → **Import**. The quiz arrives unpublished, so you can check it first.

## Limits
- Images, equations and tables inside questions aren't converted yet; add them in Canvas after importing.
- Old `.doc` and `.xls` files: save them as `.docx` or `.xlsx` first.

## License
MIT. Free to use, change and share.
