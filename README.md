# Fabricius Langauge Schema

A Fabricius document is a text file containing a JSON object with a .fab file extension, which can be read, edited and transformed with Fabricius tools (or any scripting language).

## What problem does it solve?

There is no existing format for encoding hieroglyphic text which links its visual, symbolic and semantic content.  This creates huge gaps between different sources of hieroglyphic content and analysis, making them difficult to work with for computing purposes.

The Fabricius document format enables each layer of content to be represented, while maintaining the links between them, providing a multi-purpose data object which supports use cases such as:

- mapping symbols to areas of an image of a text for harvesting labelled image data as an input to machine learning, or as the output from visual analysis
- linking different images of the same text to the same symbolic mapping: for example, for high and low-resolution versions of the same image, or for the photographic and illustrated (facsimile) versions of the same text
- adding translations to words and phrases representing within the symbolic sequence of the text, as a research or teaching resource, or as part of a learning exercise
- looking up glyph sequences in dictionaries or other lexical services, to speed up research or learning
- annotating an area of a text for the purposes of research documentation, collaboration or teaching

Further, it provides a standard format for the inputs and outputs of any automated techniques which are developed for working with the images or language.  For non-programmers, this format will allow them to view and work with the content using a standard set of tools, and it will encourage people to continue adopting and developing those tools.

## What are the challenges?

There are plenty, but the main ones are:

- Keeping it simple and lightweight, and avoiding complexity or dependencies on other more formal schemas
- Extensibility to handle more complex language features without introducing complexity or overheads to those working with simpler concepts
- Standardisation: of sign lists, transliteration schemes, ISO codes, fonts, etc.
- Support for multiple hieroglyphic or ancient languages
