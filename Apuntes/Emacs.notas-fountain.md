
## MANUAL Y NOTAS - fountain format ##

Hay dos tipos de comentarios: con "//" y con "/*".

## Tips & Tricks ##

- M-c to capitalize word
- M-l to downcase word
- M-u to upcase word
- M-( to insert double parentheses (e.g. good for inserting in dialog)
- M-) to move point past parentheses and insert newline
- M-{ and M-} to navigate by paragraph
- M-= to count words in region (C-x h to mark the accessible buffer first)
- M-/ to autocomplete (dabbrev)
- M-< to jump to beginning of buffer (add a numeric prefix to jump to a percentage through the buffer, e.g. C-u 7 M-< to jump to 70%)
        
To focus on only a selected region of a screenplay, select the scene/s and use C-x n n to narrow to that region. C-x n w will widen the region again.

The same applies if you want to only export a region of your screenplay. You can also set fountain-export-include-title-page to nil to omit a title page.
        
