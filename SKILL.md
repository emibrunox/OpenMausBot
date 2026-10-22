---
description: Create high-quality Pinterest image concepts,
  image-generation prompts, and SEO-ready Pin copy for individual
  QuizBombs quizzes or batches of quiz topics.
name: quizbombs-pinterest-creative
---

# QuizBombs Pinterest Creative Skill

## Purpose

Use this skill whenever the user asks to create, design, generate, plan,
or promote a QuizBombs quiz using Pinterest images or Pins.

The goal is to create an accurate, visually compelling Pinterest
creative that attracts the right audience and directs them to the
correct quiz page on QuizBombs.

Primary website: https://quizbombs.com/

The bot's identity, permanent brand rules, and overall behaviour are
defined in `SOUL.md`. This skill defines the practical workflow for
completing Pinterest promotion tasks.

## Required Inputs

Use the information supplied by the user first. Identify:

-   Quiz topic or exact quiz title.
-   Quiz URL, if provided.
-   Quiz category and intended audience.
-   Requested number of images or creative variations.
-   Any required headline, brand assets, style, or campaign constraints.

Do not ask for information that can reasonably be verified from the
supplied topic, URL, or available project files. If the exact
destination URL cannot be verified, ask the user for it or clearly mark
it as needing confirmation. Never invent a URL.

## Workflow

### Step 1: Understand the quiz

Classify the quiz into the most relevant category:

-   Personality and self-discovery.
-   IQ, logic, abstract reasoning, or puzzles.
-   Education, science, geography, vocabulary, or general knowledge.
-   Film, television, comics, anime, music, celebrities, or other
    fandoms.
-   Word games, memory games, and other interactive challenges.

Determine the likely audience, the main reason they would take the quiz,
and one truthful curiosity or challenge hook.

Do not claim that a quiz is scientifically validated, clinically
diagnostic, or an official franchise product unless reliable evidence
supplied or verified supports that claim.

### Step 2: Verify the destination

Use the exact URL supplied by the user when appropriate. If it is
missing, check available QuizBombs sitemap or project sources and verify
the relevant page before using a destination link.

The known sitemap references are:

-   https://quizbombs.com/post-sitemap.xml
-   https://quizbombs.com/page-sitemap.xml

These references may not contain every quiz URL. If the page cannot be
verified, do not guess its permalink. Ask for the URL or provide the
creative package with the destination marked `URL REQUIRED`.

### Step 3: Choose the creative concept

Create a concept specific to the quiz, not a generic template. Define:

1.  Audience and intent.
2.  Primary visual subject.
3.  Background and setting.
4.  Colour palette and lighting.
5.  Headline and supporting text.
6.  Visual hierarchy and focal point.
7.  Brand placement.
8.  Call to action.
9.  Composition and cropping safety.

Use these creative directions as starting points, not rigid templates:

-   **Personality quizzes:** expressive portraits, symbolic objects,
    identity-based hooks, imaginative settings.
-   **IQ and reasoning tests:** geometric patterns, number sequences,
    abstract shapes, puzzle motifs, clean analytical layouts.
-   **Educational quizzes:** relevant maps, scientific illustrations,
    vocabulary motifs, diagrams, or editorial-style imagery.
-   **TV, movie, anime, comic, and fandom quizzes:** cinematic
    atmosphere, dramatic lighting, genre-relevant colour, and
    fan-focused curiosity.
-   **Music and celebrity quizzes:** stage lighting, music-related
    motifs, era-inspired design, and topic-appropriate imagery.
-   **Word and memory games:** letter tiles, visual clues, bold
    typography, and playful puzzle elements.

For each creative, select one main hook. Do not overload the image with
multiple unrelated messages.

### Step 4: Apply Pinterest design specifications

Default to a vertical 2:3 composition at 1000 × 1500 pixels unless the
user requests another format or the image tool has different supported
sizes.

Design requirements:

-   Keep the key subject, headline, and call to action within a central
    safe area.
-   Establish a clear hierarchy: headline first, subject second, call to
    action and brand treatment next.
-   Make the headline readable on a mobile screen.
-   Use strong contrast, deliberate spacing, and a clear focal point.
-   Avoid clutter, tiny text, long paragraphs, and excessive decorative
    elements.
-   Include QuizBombs branding tastefully when an approved logo or brand
    asset is available.
-   Never fabricate an official logo. If no asset is available, use a
    restrained text-based `QuizBombs` brand treatment.
-   Ensure the image remains understandable when shown as a small
    Pinterest feed thumbnail.

If the user requests a different aspect ratio, follow the requested
format.

### Step 5: Write the image-generation prompt

When an image-generation tool is available and the user wants an image,
generate the image rather than returning only a prompt.

The prompt should specify:

-   The exact quiz topic and intended audience.
-   Vertical aspect ratio and composition.
-   Main subject and relevant visual details.
-   Art direction, colour palette, lighting, and atmosphere.
-   Headline text, written exactly as it should appear.
-   Typography style, placement, contrast, and text-safe areas.
-   Call to action and brand treatment.
-   High-quality finish and mobile readability.
-   Restrictions against unwanted text, watermarks, clutter, distorted
    elements, and misleading claims.

Avoid vague prompts such as "make a beautiful Pinterest image." Describe
the actual composition.

If the image tool struggles with accurate typography, generate the
visual with a clear text-safe area and use an available editing or
design workflow to add the headline. Inspect the final result if image
inspection is available.

Never say an image was generated, edited, inspected, or saved unless
that action actually succeeded.

### Step 6: Create Pinterest publishing copy

For each image, prepare the following package:

**A. Creative concept** - One or two sentences describing the hook and
visual direction.

**B. On-image headline** - Short and immediately understandable. -
Accurate to the quiz. - Curiosity-driven without deceptive clickbait.

**C. Supporting text** - Optional; use only if it adds clarity. - Keep
it brief and readable.

**D. Call to action** Choose a relevant CTA, for example: - Take the
Free Quiz - Test Your Knowledge - Discover Your Type - Challenge Your
Brain - See How Much You Know

Use only claims that match the actual page. Do not say "free" if the
relevant quiz is not free.

**E. Pinterest Pin title** - Descriptive, natural, and
keyword-relevant. - Include the main topic or search phrase where it
fits naturally. - Avoid keyword stuffing and unnecessary repetition.

**F. Pinterest description** - Explain what the quiz is and why the
intended audience may enjoy it. - Use the primary keyword and a few
relevant supporting phrases naturally. - Include a clear invitation to
take the quiz. - Do not promise results or benefits that the page does
not support.

**G. Destination URL** - Use the verified, exact quiz URL. - If
unverified, write `URL REQUIRED — verify before publishing`.

**H. Alt text** - Describe the meaningful visual content accurately. -
Include the quiz topic when relevant. - Do not turn alt text into a
keyword list.

**I. Keywords** - Provide a focused set of relevant Pinterest search
phrases. - Prioritise topic relevance and audience intent. - Do not
invent search-volume or ranking data.

**J. Hashtags** - Include a small number only when useful and
relevant. - Do not add a large block of generic hashtags.

### Step 7: Create variations for multiple Pins

When the user requests several Pins for the same quiz, vary the creative
angle rather than merely changing colours.

Potential angles include:

-   Curiosity: "Which Type Are You?"
-   Challenge: "Can You Get Every Question Right?"
-   Fandom: "How Well Do You Know This Universe?"
-   Learning: "Test What You Know."
-   Self-discovery: "Discover Your Result."
-   Puzzle: "Can You Solve This Challenge?"

Each variation must remain faithful to the quiz and its actual content.
Do not imply a score, result, feature, or question format that the quiz
does not offer.

For multiple quiz topics, give every quiz its own visual concept and
copy package. Avoid using the same headline formula and composition for
every topic.

## Accuracy, Copyright, and Trust

-   Do not fabricate facts about the quiz, its questions, scoring,
    outcomes, or features.
-   Do not make unsupported medical, psychological, educational, or IQ
    claims.
-   Do not imply a quiz is an official product of a film studio, game
    publisher, celebrity, or franchise owner.
-   For copyrighted entertainment topics, use original, appropriately
    licensed, or otherwise authorised assets. Do not copy official
    posters or promotional artwork without permission.
-   Avoid generating recognisable protected characters when the
    requested use or tool rules do not permit it. Use original
    genre-inspired imagery when appropriate.
-   Never fabricate testimonials, endorsements, awards, or popularity
    statistics.
-   Keep the creative honest: the image must represent the actual
    destination page.

## Quality-Control Checklist

Before delivering the package, check:

-   [ ] The correct quiz topic and audience are identified.
-   [ ] The concept is specific to the quiz.
-   [ ] The headline is accurate, concise, and readable.
-   [ ] The image follows the requested aspect ratio.
-   [ ] The composition has a clear focal point and safe margins.
-   [ ] The branding is tasteful and not fabricated.
-   [ ] The CTA matches the actual quiz page.
-   [ ] The destination URL is verified or clearly marked as requiring
    verification.
-   [ ] The Pin title and description are natural and relevant.
-   [ ] Alt text describes the actual image.
-   [ ] No unsupported claims, spelling errors, misleading imagery, or
    excessive text remain.
-   [ ] Any statement about image generation or publishing reflects what
    was actually completed.

## Default Output Format

Unless the user requests a different format, organise each quiz
promotion as follows:

### Quiz: \[Exact quiz title\]

**Destination URL:** \[Verified URL or URL REQUIRED\]

**Creative concept:** \[Short concept\]

**On-image headline:** \[Headline\]

**Supporting text:** \[Optional\]

**CTA:** \[Call to action\]

**Image-generation prompt:** \[Complete, ready-to-use prompt\]

**Pinterest Pin title:** \[Title\]

**Pinterest description:** \[Description\]

**Alt text:** \[Accurate visual description\]

**Keywords:** \[Relevant phrases\]

**Hashtags:** \[Optional, limited set\]

**Quality-control notes:** \[Only mention meaningful limitations or
checks still required\]

If an image was successfully generated, present it alongside the
corresponding publishing package. Do not substitute a prompt for an
image when image generation is available and the user explicitly
requested the image.

## Batch Mode

When the user supplies a list of quiz topics:

1.  Process each topic separately.
2.  Verify each destination URL independently.
3.  Create a distinct concept, headline, and image prompt for each quiz.
4.  Provide a separate Pinterest title, description, alt text, and
    keyword set for each.
5.  Clearly flag any URL or factual detail that could not be verified.
6.  Keep the final output organised by quiz so each package can be
    copied into a publishing workflow.

Do not claim to have uploaded, scheduled, or published Pins unless the
relevant service is connected, the user has authorised the action, and
the operation has succeeded.

## Success Standard

A successful Pin is visually clear, relevant to its audience, faithful
to the quiz, legible on mobile, and paired with useful search-friendly
copy and the correct destination.

Prioritise **relevance, originality, accuracy, and qualified quiz
traffic** over sensationalism or clickbait.
