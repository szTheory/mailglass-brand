# mailglass brand

Version 2.0, November 13, 2026. This is the complete text of the brand book (`mailglass-brand-book.html`), page by page, for people and AI assistants. The same rules as structured data are in `brand.json`; colors and type values in `tokens.json`; every file is explained in `assets/README.md`.

**Read this first.** Transactional email for Phoenix, with a preview and a delivery timeline. Check your email before it ships, then find out what happened to it. The name is written `mailglass`, all lowercase. Light is the default theme and dark is a full theme. The logo is the typemark: the word with its m drawn as two overlapping panes of glass, with no shape behind it and no tagline. Every delivery status is a word first, with its pane-of-glass mark and color second. The contrast pairs have stable ids (body, descriptor, caption, application-copy, link, focus, artwork, and one status pair per status) in both themes.

## Brand at a glance

See your email before it ships. Trace it after.Transactional email for Phoenix, with a preview and a delivery timeline for every email.

### Three rules

1. The name is mailglass: one word, all lowercase, even at the start of a sentence. In Elixir module names it is `Mailglass`.
2. The typemark is the logo. Put no shape behind it, and keep the tagline and the descriptor outside it.
3. A delivery status is always written as a word. The status mark and its color support the word; they do not replace it.

### Color

**Sand** #F6F1E8 **White** #FFFFFF **Espresso** #2A1D17 **Deep Glass** #0A6488 **Sand Line** #DDD3C4 **Glass** #1895C2, the glass in the logo

SentDeliveredDelayedFailedNot sent

### Type

Funnel Display for the name and headlines, Atkinson Hyperlegible Next for reading and tables, Atkinson Hyperlegible Mono for ids and code.

### Voice

A calm maintainer who has chased the same missing email before: says what happened, to which email, and what to do next.

## Positioning and values

**Transactional email for Phoenix, with a preview and a delivery timeline. Check your email before it ships, then find out what happened to it.**

### Phoenix developers

Send a password reset from my Phoenix app, see it before it ships, and know what happened to it later.

Add `{:mailglass, "~> 2.7"}`, write the email as a normal component, see it in the preview as your app will send it, and send it through the provider you already use.

### Support and admin staff

A customer says the password reset never arrived. Find that email and see what happened to it.

Search by the customer’s email address or the subject, read each email’s status and time, and know what to do next: wait, fix the address, or take the address off the suppression list.

### Maintainers and contributors

Keep the README, the docs, the admin and the preview looking like one project.

A book that says what is mailglass’s brand and what stays the host app’s, with the files to use and the rules for code colors and docs.

**Plain**

Name what the person is looking at: the email, the address, the provider, the time. Not “mailable”, “dispatch” or “event ledger”. Write “Sent with Postmark”, not “Dispatched”.

**Exact**

Show the real address, subject, time and time zone, and name the provider. “Delivered at 2:07 PM UTC”, not “a few minutes ago”.

**Honest**

Say only what mailglass knows. Sent is not delivered, and delivered means the receiving server took the email. It never means the person opened it or that it reached the inbox.

**Calm**

People open the admin because an email is missing. Say what happened, to which email, and what to do next.

**Yours**

The email belongs to the host app. mailglass’s name and logo never appear in a host app’s email to its customers, except in a footer if the host chooses.

## Messaging

### Elevator pitch

**mailglass is transactional email for Phoenix. See your email before it ships, in a preview of what your app will send. Then trace it after: every email has a delivery timeline, so when one goes missing you can see what happened to it.**

### Key messages

**See it before it ships.**

Preview the email at phone, tablet or desktop width, as your app will send it.

**Trace it after.**

Every email has a delivery timeline: each status and when it happened, so you can see where a missing email stopped.

**Your brand, not ours.**

Keep your email provider, your design and your From address. mailglass stays in your admin, out of your customers’ inbox.

### Tagline

**See your email before it ships. Trace it after.**

Sentence case, with both periods. It sits beside the logo, never in it. The descriptor “Transactional email for Phoenix, with a preview and a delivery timeline for every email.” goes under it wherever the line stands alone.

### About mailglass: approved descriptions

One line: Hex, GitHub and package listings

Transactional email for Phoenix, with a preview and a delivery timeline for every email.

Short: README opening, talk bios

mailglass is an open-source library for transactional email in Phoenix apps. It works with Swoosh, the email library new Phoenix apps include by default, and adds two things: a preview of each email as your app will send it, and a delivery timeline for every email.

Do not say

Guaranteed delivery, inbox placement, open or click tracking, compliant, bulletproof, powerful, seamless, “mail you can see through”. mailglass records what providers report; whether an email reached the inbox is not something it knows.

## The idea

**Why two panes of glass**

The name is the promise: you see your email through glass before it ships, and you look through glass at what happened to it after. Two looks at the same email, one before and one after.

The m in the logo is two panes of glass laid over each other. The first pane is the preview, your email as it will arrive. The second is the record, what happened to it once it left. Where the two overlap, at the middle stem, you are looking at one email through both, and that is where the glass shows its depth.

The shapes are plain: two arches that share a stem. On a dark ground the overlap is lighter than the panes: the glass is lit from behind, so where the sheets overlap it glows instead of going dark. The brand avoids eyes and magnifiers, which suggest watching the people who receive your email, and it avoids envelopes.

## Where the brand shows

**Full brand on mailglass’s own pages. A quiet guest in your app.**

### mailglass’s own

**README, Hex page, docs site, social card**

People deciding whether to use it.

**What shows.** The typemark, the glass colors, both themes, code colors, the tagline and descriptor.

### Inside the host app

**The admin and the preview, at a path the host app chooses**

Support staff and developers of the host app.

**What shows.** The typemark in the top row, the status marks and words, and the type. A host app may replace the typemark with its own name and logo.

### In other people’s writing

**Blog posts, talks, newsletters, other READMEs**

People writing about mailglass.

**What shows.** The typemark, unchanged, under the rules in this book. Nothing added.

The host app’s customers never see mailglass: the emails keep the host app’s design and From address. If the host app chooses, a footer may say the email was sent with mailglass, in plain text.

## Logo: on light, the default theme

**One color.** Espresso on Sand. One color is the same drawing in a single color: the overlap drops out, so the m reads as one plain arched m. Espresso on light, Bone on dark. Nothing else is redrawn.

**The m.** The symbol alone, for avatars, app icons and stickers. Where the name needs to show, use the typemark instead.

**Drawn for small sizes.** The m alone is the symbol, for avatars, app icons and stickers. The favicon is the m drawn for exactly 16 and 32 px: stems of 2 and 4 px, openings of 4 and 8 px, so the stems land on the pixel grid. At 16 px the overlap is a hairline and the m reads as a plain arched m; that is expected. Below 16 px, do not use the mark.

**Light is the default theme.** The logo has a version for each theme. On light, the word is Espresso, the panes are Glass and the overlap is Deep Glass, which is darker. On dark, the word is Bone, the panes are Glass Light and the overlap is Lit Glass, which is lighter. Use the version made for the background; do not make one by inverting the colors of the other. The typemark is the logo. Do not rearrange it, redraw the m, split the two panes apart, or tint one pane differently from the other.

## Logo: on dark

**One color.** Bone on Roast. One color is the same drawing in a single color: the overlap drops out, so the m reads as one plain arched m. Espresso on light, Bone on dark. Nothing else is redrawn.

**The m.** The symbol alone, for avatars, app icons and stickers. Where the name needs to show, use the typemark instead.

**Drawn for small sizes.** The m alone is the symbol, for avatars, app icons and stickers. The favicon is the m drawn for exactly 16 and 32 px: stems of 2 and 4 px, openings of 4 and 8 px, so the stems land on the pixel grid. At 16 px the overlap is a hairline and the m reads as a plain arched m; that is expected. Below 16 px, do not use the mark.

**Dark is a full theme.** The logo has a version for each theme. On light, the word is Espresso, the panes are Glass and the overlap is Deep Glass, which is darker. On dark, the word is Bone, the panes are Glass Light and the overlap is Lit Glass, which is lighter. Use the version made for the background; do not make one by inverting the colors of the other. The typemark is the logo. Do not rearrange it, redraw the m, split the two panes apart, or tint one pane differently from the other.

## Mark and favicon

**The m, drawn for small sizes.**

The m alone is the symbol, for avatars, app icons and stickers. The favicon is the m drawn for exactly 16 and 32 px: stems of 2 and 4 px, openings of 4 and 8 px, so the stems land on the pixel grid. At 16 px the overlap is a hairline and the m reads as a plain arched m; that is expected. Below 16 px, do not use the mark.

The browser tab follows the theme: `favicon.svg` draws the m with its overlap deeper on a light device and lighter on a dark one. The `.ico` is the light drawing only, because an ICO can’t change with the theme.

No shape behind it: the typemark sits directly on the page background. The one exception is the avatar, a 512 px square with the m on Sand or Roast, because social sites need an opaque square. A photograph or screenshot behind the logo needs a calm area at least as wide as the typemark plus its clear space.

## Clear space and minimum size

Keep clear space on every side equal to a quarter of the typemark’s height, measured from the outermost edge of the typemark. Nothing enters it: no text, edge or other logo. The square is that quarter.

### On screenshots and photographs

- Place the typemark on a calm area at least as wide as the typemark and its clear space.
- Use the light drawing on a light area and the dark drawing on a dark one. If neither reads well, move the logo.
- Do not put a shape or a shadow behind it to make it read.

### Minimum size

|   | Screen | Print |
| --- | --- | --- |
| **Typemark** | 96 px wide | 25 mm wide |
| **The m, drawn for its size** | 16 px wide | Not specified |

On screen, the typemark is never narrower than 96 px and the m never narrower than 16 px. In print, the typemark is never narrower than 25 mm.

### Color

The m is never yellow, gold, orange or red, and never sits on red. Two equal arches side by side are also the golden arches of a famous fast-food brand; the azure glass, the lit overlap and the word beside it are what keep this a different mark. Do not use a pair of arches as a pattern, a bullet or a shape elsewhere.

### Retired

The earlier mark is retired: the m as two arched windows with a pane of glass in only one of them. It needed a paragraph to explain, and its single filled window read as a doorway.

## Logo: misuse

✕Don’t stretch, squeeze or rotate the typemark.

✕Don’t recolor the glass or the word, or make the m yellow, gold or red.

✕Don’t put a tile, badge or any other shape behind the typemark.

✕Don’t add the tagline, the descriptor or any text to the typemark.

✕Don’t strike a line through the word, or add an envelope or an arrow.

✕Don’t use the dark drawing on a light page, or the light drawing on a dark one.

## Color: light, the default

**Sand**

#F6F1E8 RGB 246 241 232

The default background, in the book, the docs and the admin.

About 62% of a light screen.

**White**

#FFFFFF RGB 255 255 255

Cards, the email in the preview, and the table surface.

About 22% of a light screen.

**Espresso**

#2A1D17 RGB 42 29 23

Text and the word in the logo on light.

About 9% of a light screen.

**Deep Glass**

#0A6488 RGB 10 100 136

Links, the focus ring, the current tab and the one main button per screen. In the logo it is where the two panes overlap.

About 4% of a light screen.

**Sand Line**

#DDD3C4 RGB 221 211 196

Dividing lines. Never the only edge of a control.

About 3% of a light screen.

**Muted Espresso**

#665850

Secondary text on Sand and White.

**Sunken Sand**

#ECE5D8

The ground of a table header and a selected row, on light.

**Control Edge**

#857569

The border of an input or a button on light (3.9:1 on Sand). Dark uses #8B7D72.

**Glass**

#1895C2

The two panes of the m on light. Graphics only, never text.

## Color: dark

**Roast**

#1D1713 RGB 29 23 19

The dark background.

About 62% of a dark screen.

**Roast Surface**

#2A211B RGB 42 33 27

Cards and table surfaces on Roast.

About 22% of a dark screen.

**Bone**

#F3EEEA RGB 243 238 234

Text and the word in the logo on dark.

About 9% of a dark screen.

**Bright Glass**

#6CC6F0 RGB 108 198 240

Links, the focus ring, the current tab and the one main button per screen.

About 4% of a dark screen.

**Roast Line**

#43372E RGB 67 55 46

Dividing lines on dark.

About 3% of a dark screen.

**Muted Bone**

#B9ADA3

Secondary text on Roast and Roast Surface.

**Control Edge**

#8B7D72

The border of an input or a button on dark.

**Glass Light**

#46B6E8

The two panes of the m on dark. Graphics only, never text.

**Lit Glass**

#A8E4F7

Where the panes overlap on dark: lighter than the panes. Graphics only, never text.

## Color: delivery statuses

**Five statuses, each a word, a mark and a color.**

A delivery status is always written as a word. The status mark and its color support the word; they do not replace it.

In a list row the mark is 20 px tall, in a detail view 44 px, and never under 14 px. Shape separates the five without color: a frame or a fill, then a glyph. Failed is the only red, and the only crack.

## Color: contrast pairs

| Role | Where it is used | Light | Dark | Minimum |
| --- | --- | --- | --- | --- |
| **Body text** | README, docs, the admin and this book. | Aa14.51:1 | Aa15.39:1 | 4.5:1 |
| **Descriptor and secondary text** | The words “Transactional email for Phoenix” beside the logo, and metadata under a title. | Aa6.07:1 | Aa8.08:1 | 4.5:1 |
| **Caption and table metadata** | Captions, times and column heads on a card or table. | Aa6.83:1 | Aa7.19:1 | 4.5:1 |
| **Copy inside an application** | Text on a card in the admin, the README or a slide. | Aa16.32:1 | Aa13.69:1 | 4.5:1 |
| **Link, focus ring and current tab** | Links in running text, the 2 px focus ring and the underline of the current tab. | Aa6.58:1 | Aa8.24:1 | 4.5:1 |
| **Focus ring on the page** | The 2 px ring on a focused control, against the page. | 5.85:1 | 9.27:1 | 3:1 |
| **Logo glass** | The glass of the m against the page, read as a shape, not as text. | 3.05:1 | 7.70:1 | 3:1 |
| **Status word: Sent** | The word “Sent” in a table row or a delivery timeline. | Aa16.32:1 | Aa13.69:1 | 4.5:1 |
| **Status word: Delivered** | The word “Delivered”. | Aa6.52:1 | Aa8.19:1 | 4.5:1 |
| **Status word: Delayed** | The word “Delayed”. | Aa6.49:1 | Aa8.10:1 | 4.5:1 |
| **Status word: Failed** | The word “Failed”. | Aa6.54:1 | Aa7.32:1 | 4.5:1 |
| **Status word: Not sent** | The words “Not sent”, in Muted Espresso. | Aa6.83:1 | Aa7.19:1 | 4.5:1 |

### About these ratios

Ratios are WCAG 2.2 contrast, computed from the hex values. A pair that passes here says nothing about a whole product built with it. Glass on Sand is 3.0:1: enough for a shape, not for text. Sand Line and Roast Line only divide space and are never used for text.

### Never

- **Glass** as text of any size on Sand or White
- **Sand Line** as the only boundary of a control (use Control Edge)
- **Deep Glass** as text on Roast (use Bright Glass)
- **a status color** as the only way to tell a status: the word and the mark carry it

## Type

SemiBold (600) for the wordmark, page titles and headlines.

The wordmark, headlines in books, slides and social cards, and page titles in docs and the admin. Never for ids, addresses or code.

The wordmark is outlined from this typeface, so headlines set in it match the logo. Wide, low-contrast and a little friendly, it looks unlike the other Elixir libraries. Its l and I are nearly the same, which is why it never sets an id.

Regular (400), SemiBold (600) and Regular italic.

Body text, the admin, tables, buttons and labels.

Made so that letters are hard to mistake for each other, which matters when a support person copies an address from a screen. It holds up at 13 px in a dense list.

Regular (400) and SemiBold (600).

Anything copied or compared: ids, email addresses in a detail view, message headers, commands and code. Ligatures are off, so Elixir’s `|>` and `->` stay as typed.

Every character is distinct: the zero is slashed, the l and I differ. Slashed zeros are part of the face; in an id, that is the point.

All three families are SIL Open Font License 1.1, from Google Fonts. The license texts are in the assets fonts folder. None of the three has the arrow characters (U+2190 to U+2193): write “to” or draw the arrow.

## Type: the hierarchy

- Display: Funnel Display 600, 56 px on 59 px, tracking -0.015em. Use: Covers, slides and social cards. One line, two at most.
- Heading: Funnel Display 600, 28 px on 34 px, tracking -0.01em. Use: Page titles and section heads in docs and the admin.
- Body: Atkinson Hyperlegible Next 400, 16 px on 25 px, tracking 0. Use: README, docs and paragraphs in the admin. 62 to 72 characters a line.
- Dense text: Atkinson Hyperlegible Next 400, 13 px on 18 px, tracking 0. Use: Lists of emails in the admin. Always with tabular numerals.
- Label: Atkinson Hyperlegible Next 600, 12 px on 14 px, tracking 0.02em. Use: Column heads and small labels. Sentence case, never capitals.
- Code and ids: Atkinson Hyperlegible Mono 400, 13 px on 20 px, tracking 0. Use: Ids, addresses in a detail view, headers, commands. Clicking an id copies it.

## Type: in a dense list

13 px Atkinson Hyperlegible Next with tabular numerals for times and words; ids and addresses in 13 px Atkinson Hyperlegible Mono. The times line up by digit, and each status is the mark and its word.

### Made for lists people read closely

- Figures in a column use tabular numerals (`font-variant-numeric: tabular-nums`) so digits stack.
- Every id, header name and command is set in Atkinson Hyperlegible Mono, so it can be compared by eye. Funnel Display never sets one.
- Clicking an id copies it and shows a short “Copied to clipboard” message. The id itself never moves or changes.
- Headlines are sentence case, and no type is lighter than 400 or smaller than 12 px.
- Code ligatures are off (`font-variant-ligatures: none`), so `|>` and `->` stay as typed.

## Voice: the tone dial

**A calm maintainer who has chased the same missing email before: says what happened, to which email, and what to do next.**

- The admin: errors and empty states: 0 of 4 toward lively. “No emails match these filters. Try a wider date range or clear a filter.”
- Docs and README: 1 of 4 toward lively. “Preview the email before you send it.”
- Release notes: 1 of 4 toward lively. “The preview now shows the email at 375, 768 and 1024 px wide.”
- Talks and social posts: 2 of 4 toward lively. “Somebody asked where their password reset went. Here is how to find out.”

The voice never changes; the tone shifts with where the words appear. mailglass stays plain everywhere and gets only a little looser in a talk or a post. It is never loose where an email has gone missing, because people open the admin when they need an answer.

## Voice: this, not that

- Say: “Email never arrived? Start here.” Not: “Troubleshoot delivery anomalies.”
- Say: “Sent with Postmark. The receiving server has not confirmed it yet.” Not: “Your email was sent successfully.”
- Say: “Delivered: the receiving server took the email. It may not be in the inbox.” Not: “Delivered to the inbox.”
- Say: “Not sent: the address is on your suppression list.” Not: “Oops! Something went wrong.”
- Say: “Delayed: the receiving server said to try again later. Next try at 2:12 PM UTC.” Not: “Your message is in limbo.”
- Say: “Preview the email before you send it.” Not: “Preview your messages with our powerful renderer.”
- Say: “Remove this address from the suppression list.” Not: “Unblock recipient.”
- Say: “3 provider reports match no email.” Not: “You have 3 orphans.”

### Write for the people reading

- **Write for support staff who don’t read code.** Name the address, the subject and the provider before any id.
- **Say what they can do next.** Every empty and error state ends with a next step.
- **Spell out the time zone.** Write “2:07 PM UTC”, never a bare time. In a narrow column the zone sits under the time.

## How to write our name

**mailglass**

mailglass, one word, all lowercase, everywhere, including the start of a sentence (reword the sentence if it reads badly). Elixir module names force `Mailglass`; in code, packages and commands it is `mailglass`, `:mailglass` and `mix mailglass.install`.

### Not like this

- ~~Mailglass, MailGlass~~: one word, all lowercase (modules excepted)
- ~~Mail Glass, mail glass~~: one word
- ~~MAILGLASS~~: except as a label in a code comment
- ~~the mailglass platform~~: mailglass is a library

### Describing it

Call it “transactional email for Phoenix”. Say “email”, and “mailer” for the module that builds one kind of email. Call the record mailglass keeps for each email its “delivery timeline”.

## Key terms

**The words mailglass depends on.**

| Term | What it means here | Instead of |
| --- | --- | --- |
| **Email** | One message your app sends, such as a password reset. `Mailable` is only its name in code. | ~~mailable~~, ~~message (in screens)~~ |
| **Mailer** | The module in your app that builds one kind of email. | ~~mailable~~ |
| **Provider** | The service that takes your email and sends it on, such as Postmark, SES, SendGrid or Mailgun. Name it when you can. | ~~vendor~~, ~~ESP~~, ~~adapter~~ |
| **Sent** | Your app handed the email to the provider. Not the same as delivered. The event name in code is accepted. | ~~dispatched~~, ~~accepted~~ |
| **Delivered** | The receiving server took the email. It never means the person opened it or that it reached the inbox. | ~~received~~, ~~inboxed~~ |
| **Delayed** | The receiving server said to try again later, and the provider will retry. The event name in code is deferred. | ~~deferred~~, ~~soft bounce~~, ~~stuck~~ |
| **Failed** | The email did not get through and will not be retried. Providers call this a bounce. | ~~undeliverable~~, ~~dead~~ |
| **Not sent** | Held back: the address is on your suppression list. The event name in code is suppressed. | ~~suppressed~~, ~~blocked~~, ~~blacklisted~~ |
| **Suppression list** | Addresses mailglass will not send to, for example after a hard bounce (a permanent failure) or a spam complaint. | ~~blocklist~~, ~~blacklist~~ |
| **Delivery timeline** | One email’s statuses in order, each with its time, from sent to the provider’s most recent report. | ~~trail~~, ~~event ledger~~, ~~history~~ |
| **Unmatched events** | Reports from a provider that match no email mailglass sent. This is mailglass’s own term; on screen, say it in words: “3 provider reports match no email.” | ~~orphans~~, ~~orphan backlog~~ |
| **Inbound email** | Email your app receives. An inbound handler processes it. | ~~mailbox (in prose)~~ |
| **Preview** | An email rendered as it will be sent, by the same renderer. | ~~mock~~, ~~simulation~~ |
| **Host app** | The Phoenix app that uses mailglass. | ~~parent app~~, ~~consumer~~ |

These are only the words the brand depends on; the product docs define the rest. In prose, Mix, ExDoc, HexDocs, LiveView, HEEx, Oban, Ecto and Swoosh are written as proper names, and `mix` appears only as a command.

## Imagery: the real email

**Show the real email.**

mailglass’s pictures show the product at work, with its real words: a rendered email in the preview, one email’s delivery timeline, the Activity list and a command. They need no stock photography.

The product pictures in this book are drawings of the layout this book proposes, with invented data. They are not screenshots of the current product.

### Never

- Envelopes and paper planes
- The @ symbol
- Eyes and magnifiers
- Padlocks and shields
- Frosted glass and blur
- Cracked or broken glass as decoration
- Stock people at laptops
- Glowing data and network clouds

mailglass helps people see their own email and find what happened to it. Do not use pictures that suggest mailglass watches the people who receive email, guards email or is broken. It does none of those. The one crack in the brand is the Failed status mark, and it always has its word.

## Imagery: code colors

**Quiet code colors that never look like a status.**

| Role | Light | Dark | Colors |
| --- | --- | --- | --- |
| **Text** | #2A1D17 | #F3EEEA | Names and punctuation. |
| **Comment** | #6F6157 | #A59A90 | Comments, quiet. |
| **Keyword** | #0A6488 | #6CC6F0 | def, do, end, fn, SELECT, in the glass blue of the links. |
| **String** | #8A4B1D | #E0A878 | Strings, in a quiet brown that is not a status color. |
| **Atom** | #2F6B6B | #7FCFCF | Atoms and keys. |
| **Number** | #5C6B1E | #B7C972 | Numbers. |
| **Function** | #3F4F9E | #9DB1F0 | Function names where they are called or defined. |
| **Module** | #4A5C7A | #A9B8D6 | Module names, such as `Mailglass.Message`. |
| **Code background** | #EFE9DD | #14100D | Behind every code block. |

- No code color is the same as a status color. Code has no delivered green or failed red, so nothing in code looks like a status.
- Syntax colors are for code blocks only. Inline code in a sentence is plain Atkinson Hyperlegible Mono on a light chip, in every medium.
- ExDoc and HexDocs color their own code. The stylesheet in the assets docs folder sets these colors on ExDoc’s token classes. It has not been run in a real ExDoc build.
- GitHub highlights the code in a README itself, and mailglass does not control those colors.
- Show code that matches the current release, not pseudo-code.

# mix.exs ⏎ {:mailglass, "~> 2.7"} ⏎ ⏎ # lib/my_app/mailers/welcome.ex ⏎ def welcome(user) do ⏎ new() ⏎ |> to(user.email) ⏎ |> subject("Welcome to AtlasDesk") ⏎ end

# mix.exs ⏎ {:mailglass, "~> 2.7"} ⏎ ⏎ # lib/my_app/mailers/welcome.ex ⏎ def welcome(user) do ⏎ new() ⏎ |> to(user.email) ⏎ |> subject("Welcome to AtlasDesk") ⏎ end

SELECT recipient, status, occurred_at ⏎ FROM deliveries ⏎ WHERE status = 'deferred' ⏎ ORDER BY occurred_at DESC;

## Graphic elements

**Two graphic elements: the status mark and the glass frame.**

mailglass has two graphic elements, both made of glass. They are not interface components: buttons, tabs and inputs are drawn by the product.

- **The status mark.** One pane of glass in the state an email is in, always with its word beside it. Sent is a frame half full. Delivered is filled with a check. Delayed is a frame with a clock hand. Failed is filled with a crack. Not sent is a frame struck through. Shape separates the five without color: frame or fill, then the glyph. In a list row it is 20 px tall, in a detail view 44 px, and never under 14 px.
- **The glass frame.** A 2 px Espresso line (Bone on dark) around the preview pane, like the frame of a window around the rendered email. It frames a rendered email only. The email inside keeps its own design and colors.

The status mark is never the only carrier of a status, never decorates a page, and never appears without its word. The glass frame never wraps text that isn’t an email. The arch belongs to the logo alone.

## Themes: light, dark and system

**Light is the default. Dark is complete. System follows the device.**

### Light, the default

Sand behind White rows, Espresso text, Deep Glass links. Every text and background pair is contrast-checked.

### Dark

Roast behind Roast Surface rows, Bone text, Bright Glass links. The status marks and words use lighter tones of the same colors, and the overlap in the m is lighter than its panes.

### System

The page follows the device’s setting from the moment it loads, and the logo uses the drawing for whichever theme is showing. Choosing a theme applies it at once, with no confirm button.

## Applications: the Activity list

The Activity list. A drawing of the layout this book proposes, with invented data. It is not the product’s current screen.

### It answers one question

Email never arrived? The list opens with “Needs attention”: failed, not sent and delayed sends, each with one plain sentence of cause. Everything else is below it.

### The status is a pane of glass

Each row shows one pane of glass in the state the email is in: half full, checked, a clock hand, cracked, or struck through. The word is always beside it.

### What stays plain

No sidebar, no colored badges, no counters dressed as statistics. The counts are filters. In this picture the glass blue appears only in the logo and the current tab.

## Applications: the Activity list, dark

The same screen in dark. A drawing of the layout this book proposes, with invented data. It is not the product’s current screen.

### Same layout, same words

Only the colors change. The status words keep their meaning and each is at least 4.5:1 against the dark background.

### Roast, not gray

The background is a dark roast brown, warm, so the glass blue is the only cool color on the screen and the page keeps its character at night.

### The selected row

A darker band, never a colored bar down its side.

## Applications: one email’s delivery timeline

The delivery timelines of three emails: one failed, one delayed, one delivered. A drawing of the layout this book proposes, with invented data. It is not the product’s current screen.

### The answer first

Each timeline starts with one sentence that says whether the email arrived and why. Then come the steps, each with its time, its status and one plain sentence.

### Sent is not delivered

The first step always says that sent does not mean delivered, so nobody reads “sent” as “in the inbox”.

### What to do

Every timeline ends with the next step, including “nothing yet”.

## Applications: the preview

The preview, a pane of glass with the email inside it. A drawing of the layout this book proposes, with invented data. It is not the product’s current screen.

### A pane of glass

The real message sits in a plain frame in Espresso, with To, From and Subject below it. Nothing sits behind it but the paper.

### The host app’s design

The email keeps its own colors and button. mailglass adds nothing to it.

### The controls

Phone, Tablet and Desktop change the width of the pane. HTML, Text, Raw and Headers show the message in each form.

## Applications: README, docs and Hex

The README header: the typemark, the line and the descriptor as plain text under it. A drawing of the layout this book proposes, with invented data. It is not the product’s current screen.

A HexDocs page. ExDoc draws its own navigation; the brand sets the type and the code colors. A drawing of the layout this book proposes, with invented data. It is not the product’s current screen.

The Hex package page header. Hex draws the page; the text is the brand’s. A drawing of the layout this book proposes, with invented data. It is not the product’s current screen.

## Applications: a host app’s email

On a light email. A drawing of the layout this book proposes, with invented data. It is not the product’s current screen.

On a dark email, with the version made for a dark background. A drawing of the layout this book proposes, with invented data. It is not the product’s current screen.

### It is the host’s email

The people who receive it are the host app’s customers. The email keeps the host’s name, colors and voice.

### mailglass, if at all, in the footer

A host app may add “Sent with mailglass” in the footer, with the typemark at least 96 px wide, in the version made for the email’s background. Nothing else of mailglass appears.

### Never in the subject or the sender

The sender name and the subject line are the host’s alone.

## Applications: link preview

The link preview, 1280 by 640 px, shown at half size: the one full-bleed dark canvas, because a preview has no page behind it. A drawing of the layout this book proposes, with invented data. It is not the product’s current screen.

### One canvas

The typemark, the line, the descriptor and the m on Roast. The line is set in Funnel Display and sits beside the logo, never inside it.

### Where it is used

Link previews on social sites, the Hex package, and conference slides.

### The m on the right

The symbol alone, once, at a size where the overlap reads.

## Brand assets: which file to use

| You need | Use (in assets/) |
| --- | --- |
| Logo on a light background | `logo/mailglass-lockup-light.svg` `logo/mailglass-mark-light.svg` `logo/mailglass-lockup-light-2048.png` |
| Logo on a dark background | `logo/mailglass-lockup-dark.svg` `logo/mailglass-mark-dark.svg` `logo/mailglass-lockup-dark-2048.png` |
| One color: print and single-color jobs | `logo/mailglass-lockup-mono-ink.svg` `logo/mailglass-lockup-mono-bone.svg` `logo/mailglass-mark-mono-ink.svg` `logo/mailglass-mark-mono-bone.svg` |
| Favicon (the m, drawn for 16 and 32 px) | `icon/favicon.svg` `icon/favicon.ico` `icon/favicon-32-light.png` `icon/favicon-16-light.png` |
| Avatar (a 512 px square, the one logo with a plate) | `avatar/mailglass-avatar-light.svg` `avatar/mailglass-avatar-dark.svg` `avatar/mailglass-avatar-512-light.png` `avatar/mailglass-avatar-512-dark.png` |
| README header | `readme/mailglass-header-light.svg` `readme/mailglass-header-dark.svg` `readme/header-snippet.html` |
| Link preview and social card | `social/mailglass-social-card-1280x640.png` |
| Docs: code colors for ExDoc | `docs/mailglass-exdoc.css` |
| Fonts | `fonts/web/fonts.css` `fonts/variable/FunnelDisplay[wght].ttf` `fonts/variable/AtkinsonHyperlegibleNext[wght].ttf` `fonts/variable/AtkinsonHyperlegibleMono[wght].ttf` `fonts/OFL-FunnelDisplay.txt` `fonts/OFL-AtkinsonHyperlegibleNext.txt` `fonts/OFL-AtkinsonHyperlegibleMono.txt` |

## Contact, approval and legal

**Who to ask, and what’s ours.**

### Contact and approval

- Questions about the brand and requests to use it: the mailglass maintainers, through the project’s issue tracker.
- Approval: the maintainers approve any use that changes the logo or colors; unchanged use under these rules needs no approval.

### Use by others

- Hex packages, blogs, newsletters and conference sites may use the typemark unchanged to refer to mailglass.
- Do not use it to suggest that mailglass endorses or certifies another product.
- Do not alter the logo, or build a new logo from the m or its panes.

### Legal

- mailglass is released under the MIT license. The logo and this brand book are covered by the same license unless the repository says otherwise.
- No trademark registration is claimed in this book, and none was searched. Use ™, not ®, only if the maintainers decide to claim the name.
- Fonts are SIL Open Font License 1.1; their license texts ship in the assets folder.

### Revision history

**Version 2.0**, November 13, 2026. This edition replaces the earlier brand book. The m is now two overlapping panes of glass, in azure, set in espresso on sand. Retires the sealed-flap mark, the navy and teal colors, Inter and IBM Plex Mono. Adds the five delivery statuses as panes of glass, light as the default theme with a complete dark theme, and code colors for ExDoc and the applications.

## Considered and not needed

**Mascot**

Considered, not proposed. A library trusted for being exact and calm gains nothing from a character.

**Patterns and textures**

The status mark is the only graphic device. A pattern would compete with a dense list, where the words are the picture.

**Stock photography**

There is no honest photograph of “what happened to an email”. Real product pictures say it better.

**A second typeface for the logo**

The wordmark and the headlines are both set in Funnel Display, so no other display face is needed.

**Brand-colored tables**

In a dense list the words should carry the color. Rows stay on White or Roast Surface; the status mark carries the only hue.

**Logo animation and sound**

Not defined in this edition. The brand has no motion or sound rules yet; see To review.

## Retired

**What version 2.0 replaces.**

- The sealed-flap mark, the half-filled circle and the loose pane and seal vocabulary.
- The m as two arched windows with a pane of glass in only one of them, and the window as the favicon.
- Plum, lilac and orchid, the purple and pink that did not read as glass.
- The status words Accepted, Deferred and Suppressed on screen (the event names stay in code).
- “Mail you can see through.” as the lead line, and “Email, made visible.”
- The navy and teal colors, Inter and IBM Plex Mono.
- The word “Operator” beside the logo.
- The tagline inside a logo.

## To review

**Choices made in this edition that are easy to change**

1. **The name is written in lowercase.** This book writes `mailglass` everywhere, including the start of a sentence, and `Mailglass` only where an Elixir module name needs it. The README and PRODUCT.md capitalize it in prose; they would need to follow.
2. **The lead line is “See your email before it ships. Trace it after.”** It replaces “Mail you can see through.”, which two test readers took as leaky or as a privacy risk. The product’s PRODUCT.md brand line is superseded by this one.
3. **Two arches look like the McDonald’s sign.** Two equal arches side by side are that company’s mark. The azure glass, the overlap and the word are what separate them, and the rules say never yellow, gold or red. A famous mark is protected beyond its own industry, so a trademark and look-alike search is listed as not done: it is the maintainers’ or counsel’s call.
4. **The statuses use plain words, not the providers’ words.** Sent, Delivered, Delayed, Failed and Not sent replace accepted, delivered, deferred, failed and suppressed on screen. The event names stay in code and the key terms page maps them. The product’s status chips would need to follow.
5. **The admin’s main screen is called Activity.** Postmark and SendGrid call it Activity; the product calls it Deliveries. This is the maintainers’ call, so it is listed, not decided. The same goes for “Admin” rather than “Operator”.
6. **“Delivery timeline” is the product’s own word; “unmatched events” reads as jargon.** The admin’s code already calls one email’s steps its timeline, and this book now says “delivery timeline” everywhere. “Unmatched events” is the product’s term for provider reports that match no email; on screen the book says it in words. The preview’s sidebar says “Mailers”; the maintainers may want to match it.
7. **The glass is a little deeper on Sand than first drawn.** Glass on Sand is 3.0:1 so the m passes the graphics minimum; the azure moved from #1FA3D1 to #1895C2 for that.
8. **The favicon is the m, and at 16 px its overlap is a hairline.** Stems land on the pixel grid at 16 and 32 px. At 24 px and below the m can also read as two n’s. No person has looked at it at those sizes.
9. **Provider events are not mapped, and the ExDoc stylesheet is not verified.** The book gives the five statuses, not which Postmark, SES, SendGrid or Mailgun event becomes which; the maintainers own that table. The stylesheet was written from ExDoc’s class names, not run in a build.
10. **An opaque avatar exists, and there is no motion or sound yet.** The 512 px avatar is the one logo file with a solid square, because social sites need one. The logo has no animation and the brand no sound; neither is needed to use this identity.

**Not checked:** The name was kept and not cleared: a few lookups (Hex, npm, PyPI, crates, RubyGems, app stores and DNS) found no conflict, and no trademark register was searched. The logo was checked on test sheets and one blind read, not with people at 16 to 24 px, and no trademark or look-alike search was run for an arched m, including against the McDonald’s sign. The tagline was tested on two small reader tests, not on real developers. Code samples follow the README and were not run, and the ExDoc stylesheet was not run in an ExDoc build. Contrast is computed for the pairs listed here, not for a whole product. Print color was not proofed. The glass azure is 15 to 19 from light blues in two other brand books by the same maker, which is nearer than the rule of thumb of 20.
