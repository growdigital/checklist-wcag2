WebAIM's WCAG 2.0 Checklist
===========================
<http://webaim.org/standards/wcag/checklist>  
<http://www.w3.org/TR/WCAG20/>

Adapted from and copyright © 1999-2014 [WebAIM (Web Accessibility in Mind)](http://webaim.org/copyright). All rights reserved.  
May be reproduced and distributed in print or electronic format only if offered at no cost to recipients and as long as full credit is given to WebAIM.

1. Perceivable
* Operable
* Understandable
* Robuts

## 1. Perceivable

Web content is made available to the senses - sight, hearing, and/or touch

### 1.1 Text Alternatives
Provide text alternatives for any non-text content

* [1.1.1 Non-text Content (Level A)](http://www.w3.org/TR/WCAG20/#text-equiv-all)
    * [ ] All images, form image buttons, and image map hot spots have appropriate, equivalent alternative text.
    * [ ] Images that do not convey content, are decorative, or contain content that is already conveyed in text are given null alt text (alt="") or implemented as CSS backgrounds. All linked images have descriptive alternative text.
    * [ ] Equivalent alternatives to complex images are provided in context or on a separate (linked and/or referenced via longdesc) page.
    * [ ] Form buttons have a descriptive value.
    * [ ] Form inputs have associated text labels.
    * [ ] Embedded multimedia is identified via accessible text.
    * [ ] Frames are appropriately titled.

### 1.2 Time-based Media
Provide alternatives for time-based media

* [1.2.1 Prerecorded Audio-only and Video-only (Level A)](http://www.w3.org/TR/WCAG20/#media-equiv-av-only-alt)
    * [ ] A descriptive text transcript (including all relevant visual and auditory clues and indicators) is provided for non-live, web-based audio (audio podcasts, MP3 files, etc.).
    * [ ] A text or audio description is provided for non-live, web-based video-only (e.g., video that has no audio track).
* [1.2.2 Captions (Prerecorded) (Level A)](http://www.w3.org/TR/WCAG20/#media-equiv-captions)
    * [ ] Synchronized captions are provided for non-live, web-based video (YouTube videos, etc.)
* [1.2.3 Audio Description or Media Alternative (Prerecorded) (Level A)](http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc)
    * [ ] A descriptive text transcript OR audio description audio track is provided for non-live, web-based video
* [1.2.4 Captions (Live) (Level AA)](http://www.w3.org/TR/WCAG20/#media-equiv-real-time-captions)
    * [ ]  Synchronized captions are provided for all live multimedia that contains audio (audio-only broadcasts, web casts, video conferences, Flash animations, etc.)
* [1.2.5 Audio Description (Prerecorded) (Level AA)](http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc-only)
    * [ ] Audio descriptions are provided for all video content
    * [ ] NOTE: Only required if the video conveys content visually that is not available in the default audio track.
* [1.2.6 Sign Language (Prerecorded) (Level AAA)](http://www.w3.org/TR/WCAG20/#media-equiv-sign)
    * [ ] A sign language video is provided for all media content that contains audio.
* [1.2.7 Extended Audio Description (Prerecorded) (Level AAA)](http://www.w3.org/TR/WCAG20/#media-equiv-extended-ad)
    * [ ] When an audio description track cannot be added to video due to audio timing (e.g., no pauses in the audio), an alternative version of the video with pauses that allow audio descriptions is provided.
* [1.2.8 Media Alternative (Prerecorded) (Level AAA)](http://www.w3.org/TR/WCAG20/#media-equiv-text-doc)
    * [ ] A descriptive text transcript is provided for all pre-recorded media that has a video track.
* [1.2.9 Audio-only (Live) (Level AAA)](http://www.w3.org/TR/WCAG20/#media-equiv-live-audio-only)
    * [ ] A descriptive text transcript (e.g., the script of the live audio) is provided for all live content that has audio.

### 1.3 Adaptable
Create content that can be presented in different ways (for example simpler layout) without losing information or structure

* [1.3.1 Info and Relationships (Level A)](http://www.w3.org/TR/WCAG20/#content-structure-separation-programmatic)
    * [ ] Semantic markup is used to designate headings (`<h1>`), lists (`<ul>`, `<ol>`, and `<dl>`), emphasized or special text (`<strong>`, `<code>`, `<abbr>`, `<blockquote>`, for example), etc. Semantic markup is used appropriately.
    * [ ] Tables are used for tabular data. Where necessary, data cells are associated with their headers. Data table captions and summaries are used where appropriate.
    * [ ] Text labels are associated with form input elements. Related form elements are grouped with fieldset/legend.
* [1.3.2 Meaningful Sequence (Level A)](http://www.w3.org/TR/WCAG20/#content-structure-separation-sequence)
    * [ ] The reading and navigation order (determined by code order) is logical and intuitive.
* [1.3.3 Sensory Characteristics (Level A)](http://www.w3.org/TR/WCAG20/#content-structure-separation-understanding)
    * [ ] Instructions do not rely upon shape, size, or visual location (e.g., "Click the square icon to continue" or "Instructions are in the right-hand column").
    * [ ] Instructions do not rely upon sound (e.g., "A beeping sound indicates you may continue.").

### 1.4 Distinguishable
Make it easier for users to see and hear content including separating foreground from background

* [1.4.1 Use of Color (Level A)](http://www.w3.org/TR/WCAG20/#visual-audio-contrast-without-color)
    * [ ] Color is not used as the sole method of conveying content or distinguishing visual elements.
    * [ ] Color alone is not used to distinguish links from surrounding text unless the luminance contrast between the link and the surrounding text is at least 3:1 and an additional differentiation (e.g., it becomes underlined) is provided when the link is hovered over or receives focus.
* [1.4.2 Audio Control (Level A)](http://www.w3.org/TR/WCAG20/#visual-audio-contrast-dis-audio)
    * [ ] A mechanism is provided to stop, pause, mute, or adjust volume for audio that automatically plays on a page for more than 3 seconds.
* [1.4.3 Contrast (Minimum) (Level AA)](http://www.w3.org/TR/WCAG20/#visual-audio-contrast-contrast)
    * [ ] Text and images of text have a contrast ratio of at least 4.5:1.
    * [ ] Large text (over 18 point or 14 point bold) has a contrast ratio of at least 3:1
* [1.4.4 Resize text (Level AA)](http://www.w3.org/TR/WCAG20/#visual-audio-contrast-scale)
    * [ ] The page is readable and functional when the text size is doubled.
* [1.4.5 Images of Text (Level AA)](http://www.w3.org/TR/WCAG20/#visual-audio-contrast-text-presentation)
    * [ ] If the same visual presentation can be made using text alone, an image is not used to present that text.
* [1.4.6 Contrast (Enhanced) (Level AAA)](http://www.w3.org/TR/WCAG20/#visual-audio-contrast7)
    * [ ] Text and images of text have a contrast ratio of at least 7:1.
    * [ ] Large text (over 18 point or 14 point bold) has a contrast ratio of at least 4.5:1
* [1.4.7 Low or No Background Audio (Level AAA)](http://www.w3.org/TR/WCAG20/#visual-audio-contrast-noaudio)
    * [ ] Audio of speech has no or very low background noise so the speech is easily distinguished.
* [1.4.8 Visual Presentation (Level AAA)](http://www.w3.org/TR/WCAG20/#visual-audio-contrast-visual-presentation)
    * [ ] Blocks of text over one sentence in length:
        * [ ] Are no more than 80 characters wide.
        * [ ] Are NOT fully justified (aligned to both the left and the right margins).
        * [ ] Have adequate line spacing (at least 1/2 the height of the text) and paragraph spacing (1.5 times line spacing).
        * [ ] Have a specified foreground and background color. These can be applied to specific elements or to the page as a whole using CSS (and thus inherited by all other elements).
        * [ ] Do NOT require horizontal scrolling when the text size is doubled.
* [1.4.9 Images of Text (No Exception) (Level AAA)](http://www.w3.org/TR/WCAG20/#visual-audio-contrast-text-images)
    * [ ] Text is used within an image only for decoration (image does not convey content) OR when the information cannot be presented with text alone.

---

## 2. Operable
Interface forms, controls, and navigation are operable

### 2.1 Keyboard Accessible
Make all functionality available from a keyboard

* [2.1.1 Keyboard (Level A)](http://www.w3.org/TR/WCAG20/#keyboard-operation-keyboard-operable)
    * [ ] All page functionality is available using the keyboard, unless the functionality cannot be accomplished in any known way using a keyboard (e.g., free hand drawing).
    * [ ] Page-specified shortcut keys and accesskeys (accesskey should typically be avoided) do not conflict with existing browser and screen reader shortcuts.
* [2.1.2 No Keyboard Trap (Level A)](http://www.w3.org/TR/WCAG20/#keyboard-operation-trapping)
    * [ ] Keyboard focus is never locked or trapped at one particular page element. The user can navigate to and from all navigable page elements using only a keyboard.
* [2.1.3 Keyboard (No Exception) (Level AAA)](http://www.w3.org/TR/WCAG20/#keyboard-operation-all-funcs)
    * [ ] All page functionality is available using the keyboard.

### 2.2 Enough Time
Provide users enough time to read and use content

* [2.2.1 Timing Adjustable (Level A)](http://www.w3.org/TR/WCAG20/#time-limits-required-behaviors)
    * [ ] If a page or application has a time limit, the user is given options to turn off, adjust, or extend that time limit. This is not a requirement for real-time events (e.g., an auction), where the time limit is absolutely required, or if the time limit is longer than 20 hours.
* [2.2.2 Pause, Stop, Hide (Level A)](http://www.w3.org/TR/WCAG20/#time-limits-pause)
    * [ ] Automatically moving, blinking, or scrolling content that lasts longer than 5 seconds can be paused, stopped, or hidden by the user. Moving, blinking, or scrolling can be used to draw attention to or highlight content as long as it lasts less than 5 seconds.
    * [ ] Automatically updating content (e.g., automatically redirecting or refreshing a page, a news ticker, AJAX updated field, a notification alert, etc.) can be paused, stopped, or hidden by the user or the user can manually control the timing of the updates.
* [2.2.3 No Timing (Level AAA)](http://www.w3.org/TR/WCAG20/#time-limits-no-exceptions)
    * [ ] The content and functionality has no time limits or constraints.
* [2.2.4 Interruptions (Level AAA)](http://www.w3.org/TR/WCAG20/#time-limits-postponed)
    * [ ] Interruptions (alerts, page updates, etc.) can be postponed or suppressed by the user.
* [2.2.5 Re-authenticating (Level AAA)](http://www.w3.org/TR/WCAG20/#time-limits-server-timeout)
    * [ ] If an authentication session expires, the user can re-authenticate and continue the activity without losing any data from the current page.

### 2.3 Seizures
Do not design content in a way that is known to cause seizures

* [2.3.1 Three Flashes or Below Threshold (Level A)](http://www.w3.org/TR/WCAG20/#seizure-does-not-violate)
    * [ ] No page content flashes more than 3 times per second unless that flashing content is sufficiently small and the flashes are of low contrast and do not contain too much red. (See general flash and red flash thresholds)
* [2.3.2 Three Flashes (Level AAA)](http://www.w3.org/TR/WCAG20/#seizure-three-times)
    * [ ] No page content flashes more than 3 times per second.

### 2.4 Navigable
Provide ways to help users navigate, find content, and determine where they are

* [2.4.1 Bypass Blocks (Level A)](http://www.w3.org/TR/WCAG20/#navigation-mechanisms-skip)
    * [ ] A link is provided to skip navigation and other page elements that are repeated across web pages.
    * [ ] If a page has a proper heading structure, this may be considered a sufficient technique instead of a "Skip to main content" link. Note that navigating by headings is not yet supported in all browsers.
    * [ ] If a page uses frames and the frames are appropriately titled, this is a sufficient technique for bypassing individual frames.
* [2.4.2 Page Titled (Level A)](http://www.w3.org/TR/WCAG20/#navigation-mechanisms-title)
    * [ ] The web page has a descriptive and informative page title.
* [2.4.3 Focus Order (Level A)](http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-order)
    * [ ] The navigation order of links, form elements, etc. is logical and intuitive.
* [2.4.4 Link Purpose (In Context) (Level A)](http://www.w3.org/TR/WCAG20/#navigation-mechanisms-refs)
    * [ ] The purpose of each link (or form image button or image map hotspot) can be determined from the link text alone, or from the link text and its context (e.g., surrounding paragraph, list item, table cell, or table headers).
    * [ ] Links (or form image buttons) with the same text that go to different locations are readily distinguishable.
* [2.4.5 Multiple Ways (Level AA)](http://www.w3.org/TR/WCAG20/#navigation-mechanisms-mult-loc)
    * [ ] Multiple ways are available to find other web pages on the site - at least two of: a list of related pages, table of contents, site map, site search, or list of all available web pages.
* [2.4.6 Headings and Labels (Level AA)](http://www.w3.org/TR/WCAG20/#navigation-mechanisms-descriptive)
    * [ ] Page headings and labels for form and interactive controls are informative. Avoid duplicating heading (e.g., "More Details") or label text (e.g., "First Name") unless the structure provides adequate differentiation between them.
* [2.4.7 Focus Visible (Level AA)](http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-visible)
    * [ ] It is visually apparent which page element has the current keyboard focus (i.e., as you tab through the page, you can see where you are).
* [2.4.8 Location (Level AAA)](http://www.w3.org/TR/WCAG20/#navigation-mechanisms-location)
    * [ ] If a web page is part of a sequence of pages or within a complex site structure, an indication of the current page location is provided, for example, through breadcrumbs or specifying the current step in a sequence (e.g., "Step 2 of 5 - Shipping Address").
* [2.4.9 Link Purpose (Link Only) (Level AAA)](http://www.w3.org/TR/WCAG20/#navigation-mechanisms-link)
    * [ ] The purpose of each link (or form image button or image map hotspot) can be determined from the link text alone.
    * [ ] There are no links (or form image buttons) with the same text that go to different locations.
* [2.4.10 Section Headings (Level AAA)](http://www.w3.org/TR/WCAG20/#navigation-mechanisms-headings)
    * [ ] Beyond providing an overall document structure, individual sections of content are designated using headings, where appropriate.

---

## 3. Understandable
Content and interface are understandable

### 3.1 Readable
Make text content readable and understandable

* [3.1.1 Language of Page (Level A)](http://www.w3.org/TR/WCAG20/#meaning-doc-lang-id)
  * [ ] The language of the page is identified using the HTML lang attribute (`<html lang="en">`, for example).
* [3.1.2 Language of Parts (Level AA)](http://www.w3.org/TR/WCAG20/#meaning-other-lang-id)
  * [ ] The language of page content that is in a different language is identified using the lang attribute (e.g., `<blockquote lang="es">`).
* [3.1.3 Unusual Words (Level AAA)](http://www.w3.org/TR/WCAG20/#meaning-idiom)
  * [ ] Words that may be ambiguous, unknown, or used in a very specific way are defined through adjacent text, a definition list, a glossary, or other suitable method.
* [3.1.4 Abbreviations (Level AAA)](http://www.w3.org/TR/WCAG20/#meaning-located)
  * [ ] Expansions for abbreviations are provided by expanding or explaining the definition the first time it is used, using the `<abbr>` element, or linking to a definition or glossary. NOTE: WCAG 2.0 gives no exception for regularly understood abbreviations (e.g., "HTML" on a web design site must always be expanded).
* [3.1.5 Reading Level (Level AAA)](http://www.w3.org/TR/WCAG20/#meaning-supplements)
  * [ ] A more understandable alternative is provided for content that is more advanced than can be reasonably read by a person with roughly 9 years of primary education.
* [3.1.6 Pronunciation (Level AAA)](http://www.w3.org/TR/WCAG20/#meaning-pronunciation)
  * [ ] If the pronunciation of a word is vital to understanding that word, its pronunciation is provided immediately following the word or via a link or glossary.

### 3.2 Predictable
Make Web pages appear and operate in predictable ways

* [3.2.1 On Focus (Level A)](http://www.w3.org/TR/WCAG20/#consistent-behavior-receive-focus)
    * [ ] When a page element receives focus, it does not result in a substantial change to the page, the spawning of a pop-up window, an additional change of keyboard focus, or any other change that could confuse or disorient the user.
* [3.2.2 On Input (Level A)](http://www.w3.org/TR/WCAG20/#consistent-behavior-unpredictable-change)
    * [ ] When a user inputs information or interacts with a control, it does not result in a substantial change to the page, the spawning of a pop-up window, an additional change of keyboard focus, or any other change that could confuse or disorient the user unless the user is informed of the change ahead of time.
* [3.2.3 Consistent Navigation (Level AA)](http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-locations)
    * [ ] Navigation links that are repeated on web pages do not change order when navigating through the site.
* [3.2.4 Consistent Identification (Level AA)](http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-functionality)
    * [ ] Elements that have the same functionality across multiple web pages are consistently identified. For example, a search box at the top of the site should always be labeled the same way.
* [3.2.5 Change on Request (Level AAA)](http://www.w3.org/TR/WCAG20/#consistent-behavior-no-extreme-changes-context)
    * [ ] Substantial changes to the page, the spawning of pop-up windows, uncontrolled changes of keyboard focus, or any other change that could confuse or disorient the user must be initiated by the user. Alternatively, the user is provided an option to disable such changes.

### 3.3 Input Assistance
Help users avoid and correct mistakes

* [3.3.1 Error Identification (Level A)](http://www.w3.org/TR/WCAG20/#minimize-error-identified)
    * [ ] Required form elements or form elements that require a specific format, value, or length provide this information within the element's label.
    * [ ] If utilized, form validation errors are presented in an efficient, intuitive, and accessible manner. The error is clearly identified, quick access to the problematic element is provided, and user is allowed to easily fix the error and resubmit the form.
* [3.3.2 Labels or Instructions (Level A)](http://www.w3.org/TR/WCAG20/#minimize-error-cues)
    * [ ] Sufficient labels, cues, and instructions for required interactive elements are provided via instructions, examples, properly positioned form labels, and/or fieldsets/legends.
* [3.3.3 Error Suggestion (Level AA)](http://www.w3.org/TR/WCAG20/#minimize-error-suggestions)
    * [ ] If an input error is detected (via client-side or server-side validation), provide suggestions for fixing the input in a timely and accessible manner.
* [3.3.4 Error Prevention (Legal, Financial, Data) (Level AA)](http://www.w3.org/TR/WCAG20/#minimize-error-reversible)
    * [ ] If the user can change or delete legal, financial, or test data, the changes/deletions can be reversed, verified, or confirmed.
* [3.3.5 Help (Level AAA)](http://www.w3.org/TR/WCAG20/#minimize-error-context-help)
    * [ ] Provide instructions and cues in context to help in form completion and submission.
* [3.3.6 Error Prevention (All) (Level AAA)](http://www.w3.org/TR/WCAG20/#minimize-error-reversible-all)
    * [ ] If the user can submit information, the submission is reversible, verified, or confirmed.

---

## 4. Robust
Content can be used reliably by a wide variety of user agents, including assistive technologies

### 4.1 Compatible
Maximize compatibility with current and future user agents, including assistive technologies

* [4.1.1 Parsing (Level A)](http://www.w3.org/TR/WCAG20/#ensure-compat-parses)
    * [ ] Significant HTML/XHTML validation/parsing errors are avoided. Check at http://validator.w3.org/
* [4.1.2 Name, Role, Value (Level A)](http://www.w3.org/TR/WCAG20/#ensure-compat-rsv)
    * [ ] Markup is used in a way that facilitates accessibility. This includes following the HTML/XHTML specifications and using forms, form labels, frame titles, etc. appropriately.

---

## Notes


Uses GitHub style Tasks Lists:  
<https://github.com/blog/1375%0A-task-lists-in-gfm-issues-pulls-comments>