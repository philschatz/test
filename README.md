# Inline.class

This element extends an existing defition

Children:

* [math](#math)

true false
# id.attrib.required

Children:

* ID.datatype

# table.attlist

This element extends an existing defition

Children:

* Text.datatype
* Text.datatype
* Number.datatype
* Number.datatype

# caption

This element extends an existing defition

Children:

* [caption.attlist](#caption.attlist)
* [Content.InlineTitle](#Content.InlineTitle)
* [Inline.model](#Inline.model)

# enum.attr.td.data-valign

# enum.attr.td.data-align

# td.attlist

This element extends an existing defition

Children:

* [enum.attr.td.data-valign](#enum.attr.td.data-valign)
* [enum.attr.td.data-align](#enum.attr.td.data-align)

# th.attlist

This element extends an existing defition

Children:

* [enum.attr.td.data-valign](#enum.attr.td.data-valign)
* [enum.attr.td.data-align](#enum.attr.td.data-align)

# enum.attr.ol.data-number-style

# enum.attr.ol.data-mark-suffix

# ol.attlist

This element extends an existing defition

Children:

* [enum.attr.ol.data-number-style](#enum.attr.ol.data-number-style)
* [enum.attr.ol.data-mark-suffix](#enum.attr.ol.data-mark-suffix)
* [enum.attr.ol.data-mark-suffix](#enum.attr.ol.data-mark-suffix)

# enum.attr.ul.data-bullet-style

# ul.attlist

This element extends an existing defition

Children:

* [enum.attr.ul.data-bullet-style](#enum.attr.ul.data-bullet-style)
* [enum.attr.ol.data-mark-suffix](#enum.attr.ol.data-mark-suffix)

# li.attlist

This element extends an existing defition

Children:

* Text.datatype
* Text.datatype
* Text.datatype

# enum.attr.img.data-media-type

# img.attlist

This element extends an existing defition

Children:

* [enum.attr.img.data-media-type](#enum.attr.img.data-media-type)
* URI.datatype
* Length.datatype
* Boolean.datatype

# enum.attr.strong.data-effect

# strong.attlist

This element extends an existing defition

Children:

* [enum.attr.strong.data-effect](#enum.attr.strong.data-effect)

# enum.attr.em.data-effect

# em.attlist

This element extends an existing defition

Children:

* [enum.attr.em.data-effect](#enum.attr.em.data-effect)

# enum.attr.span.data-type

# span.attlist

This element extends an existing defition

Children:

* [enum.attr.span.data-type](#enum.attr.span.data-type)
* Text.datatype

# enum.attr.Heading.data-type

# Heading.attrib

This element extends an existing defition

Children:

* [enum.attr.Heading.data-type](#enum.attr.Heading.data-type)

# div.attlist

This element extends an existing defition

Children:

* Text.datatype
* Text.datatype

# Content.Space

Children:

* Number.datatype
* Text.datatype

# Content.Term

Children:

* [id.attrib](#id.attrib)
* [class.attrib](#class.attrib)
* [Inline.model](#Inline.model)

# Content.Foreign

Children:

* [Inline.model](#Inline.model)

# Content.FootnoteNumber

Children:

* [id.attrib.required](#id.attrib.required)
* URI.datatype
* Number.datatype

# Content.ImageWithThumbnail

Children:

* URI.datatype
* [img](#img)

# Content.FootnoteRefs

Children:

* [id.attrib.required](#id.attrib.required)
* URI.datatype
* Number.datatype
* [Inline.model](#Inline.model)

# Content.Title.optional

Children:

* [Common.attrib](#Common.attrib)
* [Flow.model](#Flow.model)

# Content.Note.attrs

Children:

* [Common.attrib](#Common.attrib)
* Text.datatype
* Text.datatype
* [Content.Title.optional](#Content.Title.optional)

# Content.Note

Children:

* [Content.Note.attrs](#Content.Note.attrs)
* [Flow.model](#Flow.model)

# Content.Equation

Children:

* [Content.Note.attrs](#Content.Note.attrs)
* [Flow.model](#Flow.model)

# Content.Problem

Children:

* [Content.Note.attrs](#Content.Note.attrs)
* [Flow.model](#Flow.model)

# Content.Solution

Children:

* [Content.Note.attrs](#Content.Note.attrs)
* [Flow.model](#Flow.model)

# Content.Commentary

Children:

* [Content.Note.attrs](#Content.Note.attrs)
* [Flow.model](#Flow.model)

# Content.Exercise

Children:

* [Content.Note.attrs](#Content.Note.attrs)
* [Content.Problem](#Content.Problem)
* [Content.Solution](#Content.Solution)
* [Content.Commentary](#Content.Commentary)

# Content.Example

Children:

* [Content.Note.attrs](#Content.Note.attrs)
* [Flow.model](#Flow.model)

# Content.Newline.class

Children:

* [Content.Note.attrs](#Content.Note.attrs)
* Number.datatype
* [br](#br)

# div-span-list.attrs

Children:

* Text.datatype
* Text.datatype
* [enum.attr.ul.data-bullet-style](#enum.attr.ul.data-bullet-style)
* [enum.attr.ol.data-number-style](#enum.attr.ol.data-number-style)
* [Content.Note.attrs](#Content.Note.attrs)

# Content.DivList

Children:

* [div-span-list.attrs](#div-span-list.attrs)
* [Content.DivListItem](#Content.DivListItem)

# Content.DivListItem

Children:

* [Content.Note.attrs](#Content.Note.attrs)
* [Flow.model](#Flow.model)

# Content.SpanList

Children:

* [div-span-list.attrs](#div-span-list.attrs)
* [Content.SpanListItem](#Content.SpanListItem)

# Content.SpanListItem

Children:

* [Content.Note.attrs](#Content.Note.attrs)
* [Inline.model](#Inline.model)

# Content.ListWithTitle

Children:

* [id.attrib.required](#id.attrib.required)
* [id.attrib](#id.attrib)
* [Inline.model](#Inline.model)
* [ul](#ul)
* [ol](#ol)
* [Content.DivList](#Content.DivList)

# Content.ParaWithTitle

Children:

* [p.attlist](#p.attlist)
* [Content.InlineTitle](#Content.InlineTitle)
* [Inline.model](#Inline.model)

# Content.Alternates.class

Children:

* [id.attrib.required](#id.attrib.required)
* Text.datatype
* [img](#img)
* [Content.ImageWithThumbnail](#Content.ImageWithThumbnail)

# Content.Media.class

Children:

* [id.attrib.required](#id.attrib.required)
* Text.datatype
* Text.datatype
* [img](#img)
* [iframe](#iframe)

# u

Children:

* [u.attlist](#u.attlist)
* [Inline.model](#Inline.model)

# u.attlist

Children:

* [Common.attrib](#Common.attrib)

# ol.attlist

This element extends an existing defition

# Content.Glossary

Children:

* [dl](#dl)

# Content.InlineTitle

Children:

* [Inline.model](#Inline.model)

# Block.class

This element extends an existing defition

Children:

* [section](#section)
* [figure](#figure)
* [Content.Note](#Content.Note)
* [Content.Equation](#Content.Equation)
* [Content.Exercise](#Content.Exercise)
* [Content.Example](#Content.Example)
* [Content.DivList](#Content.DivList)
* [Content.ListWithTitle](#Content.ListWithTitle)
* [Content.ParaWithTitle](#Content.ParaWithTitle)
* [Content.Media.class](#Content.Media.class)
* [Content.Alternates.class](#Content.Alternates.class)
* [Content.Newline.class](#Content.Newline.class)
* [Content.FootnoteRefs](#Content.FootnoteRefs)

# Inline.class

This element extends an existing defition

Children:

* [u](#u)
* [Content.SpanList](#Content.SpanList)
* [Content.Space](#Content.Space)
* [Content.FootnoteNumber](#Content.FootnoteNumber)
* [Content.Term](#Content.Term)
* [Content.Foreign](#Content.Foreign)
* [Content.Media.class](#Content.Media.class)
* [Content.Alternates.class](#Content.Alternates.class)
* [Content.Newline.class](#Content.Newline.class)

# section

Children:

* [section.attlist](#section.attlist)
* [Heading.class](#Heading.class)
* [Flow.model](#Flow.model)

# section.attlist

Children:

* [Common.attrib](#Common.attrib)
* Number.datatype
* Text.datatype
* Text.datatype

# figure

Children:

* [figure.attlist](#figure.attlist)
* [Content.Title.optional](#Content.Title.optional)
* [figcaption](#figcaption)
* [Flow.model](#Flow.model)

# figure.attlist

Children:

* [Common.attrib](#Common.attrib)
* Text.datatype

# figcaption

Children:

* [figcaption.attlist](#figcaption.attlist)
* [Content.InlineTitle](#Content.InlineTitle)
* [Flow.model](#Flow.model)

# figcaption.attlist

Children:

* [id.attrib](#id.attrib)

# cnx-pi

Children:

* [cnx-pi.attlist](#cnx-pi.attlist)
* cnx-pi.datatype

# cnx-pi.attlist

Children:

* Text.datatype

# Block.class

This element extends an existing defition

Children:

* [cnx-pi](#cnx-pi)

