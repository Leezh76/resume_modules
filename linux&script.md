## linux and script skills
### linux skills
1. install Archlinux only refering to manual, familiar with common commands, able to check the log
2. use emacs as daily drive editor
   and familiar with elisp or scheme, have functional programming language knowledge
3. familiar with opensource culture
   play a ArchLinux irc

### script skills
1. python
   + use for text processing, file renaming or regex expression
   + in crypto class, use encryption
   + in formal method fundation using `z3-solver`
2. scheme and lisp
   + used for config emacs
   + SICP, the most important book I've learned, it give me feeling program can be something really flexible
   ```scheme
   (define (cons x y) (lambda (f) (f x y)))
   (define (car p) (p (lambda (x y) x)))
   (define (cdr p) (p (lambda (x y) y)))
   ```
3. language design ability
   used to design a language core, with time limits
   know the interpreter process
   have good instinct

