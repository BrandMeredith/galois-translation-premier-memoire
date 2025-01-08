- Start with a public domain copy of the document:
  - [Premier Memoire - French](https://github.com/BrandMeredith/galois-translation-premier-memoire/blob/main/galois_premier_memoir_french_full.pdf)
  - Sourced from the Project Gutenberg book [Œuvres mathématiques d'Évariste Galois by Évariste Galois](https://www.gutenberg.org/ebooks/40213)
  - This book was published in 1897 "under the auspices of the Mathematical Society of France" over 60 years after Galois wrote his Premier Memoire.

- Convert the PDF to one JPEG per page (ChatGPT o1 doesn't accept PDFs):
  - Ask ChatGPT 4o: "Please convert the attached pdf to a series of jpegs, one for each page."

- Ask ChatGPT o1 to translate a page for you:
  - "Please translate the attached pages from french into english, in order. Please write the translation to a txt file in the language of LaTeX."
  - o1 can take 4 pages at once. The above prompt won't provide a .txt file, but rather just a better-formatted code box for copying and pasting.

- Copy and paste the code into Overleaf:
  - https://www.overleaf.com/project/67784f5cf057f2459e85750f
 
- Edit this as you will.

- Have Overleaf compile the code into a pdf document which you can save in Github:
  - https://github.com/BrandMeredith/galois-translation-premier-memoire/blob/main/galois_premier_memoir_translation.pdf
