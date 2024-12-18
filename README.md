# Software Development Links

## IDEs

"Zed is a next-generation code editor designed for high-performance collaboration with humans and AI.":
<https://zed.dev/>

## Code Conventions

Naming conventions:
<https://www.swyx.io/how-to-name-things>

## Fonts / Typefaces / Typography

A book! On typography! By Matthew Butterick:
<https://practicaltypography.com/>

<https://larsenwork.com/monoid/>

<https://sourcefoundry.org/hack/>

<https://monolisa.dev>

<https://github.com/tonsky/FiraCode>

IBM Plex Mono (used this on Windows):
<https://github.com/IBM/plex>

From the Berkeley Graphics site listed in the "uncategorised" section:
<https://berkeleygraphics.com/typefaces/berkeley-mono/>

<https://github.com/subframe7536/maple-font>

2024 - switched to Monaspace:
<https://github.com/githubnext/monaspace>

## AI / LLM / Artifical Intelligence

<https://github.com/AntonOsika/gpt-engineer>

LLM tutorial:
<https://jaykmody.com/blog/gpt-from-scratch/>
<https://news.ycombinator.com/item?id=34726115>

LLM Visualization (and interactive learning tool): <https://bbycroft.net/llm>

aider, "Aider is AI pair programming in your terminal": <https://aider.chat/>

Little video from Matt Pocock:
<https://x.com/mattpocockuk/status/1851599427581976691>

nanoGPT in a spreadsheet: <https://github.com/dabochen/spreadsheet-is-all-you-need>

"NotebookLM is an AI-powered research and writing assistant that works best with the sources you upload":
<https://notebooklm.google.com/>

"Text to Math Animations, powered by manim engine + gpt-4o": <https://visualmath-ai.vercel.app/>

Anthropic / Claude, Model Context Protocol ("The Model Context Protocol is an open standard that enables developers to build secure, two-way connections between their data sources and AI-powered tools. The architecture is straightforward: developers can either expose their data through MCP servers or build AI applications (MCP clients) that connect to these servers."):

- <https://www.anthropic.com/news/model-context-protocol>
- <https://modelcontextprotocol.io/introduction>

## Tools (TODO: Some might fit better in frontend/backend specific categories)

Faster (?) cross-platform nvm: <https://github.com/Schniz/fnm>

New browser: <https://arc.net/>

Open-source Postman alternative: <https://www.usebruno.com/>

## JavaScript Ecosystem

New package registry from Ryan Dahl + Deno team:

- <https://jsr.io/docs/introduction>
- <https://deno.com/blog/jsr_open_beta>

State of JS 2024: <https://2024.stateofjs.com/en-US/>

## TypeScript Ecosystem

Types vs. Interfaces:

- <https://stackoverflow.com/questions/37233735/interfaces-vs-types-in-typescript/52682220#52682220>
- <https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#differences-between-type-aliases-and-interfaces>

The TypeScript team's internal coding guidelines:
<https://github.com/Microsoft/TypeScript/wiki/Coding-guidelines>

React (with TypeScript) cheat sheet:
<https://github.com/typescript-cheatsheets/react>

Free[ish] books:

- <https://effectivetypescript.com/>
- <https://exploringjs.com/tackling-ts/>
- <https://basarat.gitbook.io/typescript/>

Matt Pocock tips thread:
<https://threadreaderapp.com/thread/1509964736275927042.html>

shoehorn (relax typings for tests):
<https://github.com/total-typescript/shoehorn>

Pattern matching:
<https://github.com/gvergnaud/ts-pattern>

Sindre Sorhus lib, similar to the Matt Pocock library (which I need to add):
<https://github.com/sindresorhus/type-fest/tree/main>

"Good" tricks:
<https://www.placemark.io/post/good-magic-with-typescript>

React cheatsheet:
<https://react-typescript-cheatsheet.netlify.app/>

Are The Types Wrong CLI (check that package exports are correct):
<https://github.com/arethetypeswrong/arethetypeswrong.github.io/tree/main/packages/cli>

"Effect is a powerful TypeScript library designed to help developers easily create complex, synchronous, and asynchronous programs.":
<https://effect.website/>

"TSDoc is a proposal to standardize the doc comments used in TypeScript code, so that different tools can extract content without getting confused by each other's markup.":

- <https://tsdoc.org/>
- <https://www.npmjs.com/package/@microsoft/tsdoc>

Optional vs. undefined: <https://tkdodo.eu/blog/optional-vs-undefined>

## Bun

Bun:
<https://bun.sh/>

V1 launch:
<https://bun.sh/blog/bun-v1.0>

TypeScript-first web framework:
<https://elysiajs.com/>
<https://elysiajs.com/blog/with-prisma.html>

Articles on V8, C / C++, zig, systems integration:

- <https://bun.sh/blog/how-bun-supports-v8-apis-without-using-v8-part-1>
- <https://bun.sh/blog/how-bun-supports-v8-apis-without-using-v8-part-2>

## "Next-gen" native-code tooling

OXC project ("The JavaScript Oxidation Compiler"):

- <https://github.com/oxc-project/oxc>
- <https://oxc.rs/>
- Bundler/transformer: <https://oxc.rs/blog/2024-09-29-transformer-alpha.html>

Biome (formerly the Rome project):

- <https://biomejs.dev/>

Astral Python tooling (Ruff, UV):

- [<https://biomejs.dev/>](https://astral.sh/)

Rspack:

- <https://www.rspack.dev/>

Turbo:

- <https://turbo.build/pack>

Vlt / "Volt" ("VLT delivers the tools and infrastructure developers need to streamline package management, scale efficiently, and secure a faster, more tailored web experience."):

- <https://www.vlt.sh/>

Rolldown (rollup-compatible bundler in Rust, being built to replace both esbuild and rollup in the Vite project):

- <https://rolldown.rs/>

Mako from Ant Group (another Rust bundler):

- <https://makojs.dev/>

A note on Rust-based JavaScript linters and why type-linting is not available:

- https://www.joshuakgoldberg.com/blog/rust-based-javascript-linters-fast-but-no-typed-linting-right-now/

An article on Rust-based TypeScript from Matt Pocock:

- https://www.totaltypescript.com/rewriting-typescript-in-rust

Devon's video on history of bundlers ("Bundling Past, Present, and Future"): <https://www.youtube.com/watch?v=JUS6EPMbk0U>

## Frontend

### Performance

Chrome project to work w/ React frameworks to improve performance / UX:
<https://developer.chrome.com/blog/aurora-update-2023/>

Wes Bos video on the McMaster-Carr website and how it's so simple and fast:
<https://www.youtube.com/watch?v=-Ln-8QM8KhQ>

Millionjs project:

- The linter (VS Code plugin): <https://million.dev/blog/lint>
- The tool itself: <https://million.dev/docs>

### Frameworks

Mix of frameworks (some full stack, some not), stacks, starters, and tooling:

- <https://svelte.dev/>
- <https://ultrajs.dev/>
- <https://remix.run/>
- <https://blitzjs.com/>
- <https://www.solidjs.com/>
- <https://crank.js.org/>
- <https://github.com/rodinhart/metalui>
- Astro full-stack: <https://astro.build/>
- Astro-native SSG (docs-focused): <https://starlight.astro.build/>
- Vite: <https://vitejs.dev/>
- "Vite-native" testing (alternative to Jest): <https://vitest.dev/>
- Vite-and-Vue-native SSG: <https://vitepress.dev/>
- Waku, a "lightweight" RSC framework: <https://waku.gg/>
- Tanner Linsley's SPA-focused stack: <https://tanstack.com/>
- Kent Dodd's "epic stack": <https://www.epicweb.dev/epic-stack>

### ORMs

Drizzle:
<https://github.com/drizzle-team/drizzle-orm>

Prisma:
<https://www.prisma.io/>

### React

Future of React (Feb 2024): <https://react.dev/blog/2024/02/15/react-labs-what-we-have-been-working-on-february-2024>

Andrew Clark (summary of above):

```text
By the end of 2024, you’ll likely never need these APIs again:

• useMemo, useCallback, memo → React Compiler
• forwardRef → ref is a prop
• React.lazy → RSC, promise-as-child
• useContext → use(Context)
• throw promise → use(promise)
• <Context.Provider> → <Context>
```

Negative thoughts on direction of React:
[unread] <https://marmelab.com/blog/2023/06/05/react-angularjs-moment.html>

RSC: <https://twitter.com/eli_white/status/1657729306749988864>

Discussion on React server components with Ryan Carniato, Tanner Linsley, & Ben Holmes:
[unread] <https://www.youtube.com/watch?v=QRVtu9_xi2k>

The React compiler beta release:
<https://react.dev/blog/2024/10/21/react-compiler-beta-release>

React 19: <https://react.dev/blog/2024/12/05/react-19>

### Web Components

"Maybe Web Components are not the Future?": <https://dev.to/ryansolid/maybe-web-components-are-not-the-future-hfh>
"Web Components Are Not the Future": <https://dev.to/ryansolid/web-components-are-not-the-future-48bh>
"Web Components Are Not the Future — They’re the Present": <https://www.abeautifulsite.net/posts/web-components-are-not-the-future-they-re-the-present/>
"Web components are okay": <https://nolanlawson.com/2024/09/28/web-components-are-okay/>

### UI, Design, and CSS

Font stacks ("The fastest fonts available. No downloading, no layout shifts, no flashes — just instant renders."):
 
 - <https://github.com/system-fonts/modern-font-stacks>
 - <https://modernfontstacks.com/>

Next-gen "drag-and-drop":
 
 - <https://github.com/atlassian/pragmatic-drag-and-drop>
 - Older video: <https://www.youtube.com/watch?v=5SQkOyzZLHM>
 - Newer video: <https://www.youtube.com/watch?v=79kZdABVtCg>

The excellent shadcn (tailwind copy-paste "ui framework"): <https://ui.shadcn.com>

Origin UI ("Origin UI is an extensive collection of copy-and-paste components for quickly building app UIs. It‘s free, open-source, and ready to drop into your projects."): <https://originui.com/>

Devon's (Parcel) React Aria ("Over 40 components with built-in behavior, adaptive interactions, top-tier accessibility, and internationalization out of the box, ready for your styles."): <https://react-spectrum.adobe.com/react-aria/>

Senior DX engineer @ Vercel, very impressive CSS-fu:
<https://x.com/jh3yy>

Chrome CSS 2023 updates:
[unread] <https://developer.chrome.com/blog/whats-new-css-ui-2023/>

CSS transitions: <https://x.com/jh3yy/status/1869533505686036688>

Blendy ("Meet Blendy, a framework-agnostic tool that smoothly transitions one element into another with just a few lines of code."): <https://blendy.tahazsh.com/>

CSS-in-JS library with compile-time optimizations:
<https://panda-css.com/>

Panda CSS references these projects:

- Chakra UI — where it all started
- Vanilla Extract — for inspiring the utilities API
- Stitches — for inspiring the recipes and variants API
- Tailwind CSS — for inspiring the JIT compiler and strategy
- Class Variance Authority — for inspiring the cva name
- Styled System — for the initial idea of Styled Props
- Linaria — for inspiring the initial atomic css strategy
- Uno CSS — for inspiring the studio and astro integration

This blog post has lots of good information about Chakra and Panda:
<https://www.adebayosegun.com/blog/the-future-of-chakra-ui>

Determine good line heights:
<https://www.thegoodlineheight.com/>

"A look at how I solved a design problem with CSS cap unit.":
<https://ishadeed.com/article/css-cap-unit/>

Architecting design systems:
[unread] <https://blog.almaer.com/building-a-modern-design-system-in-layers/>

AWS design system, Cloudscape ("An open source design system for the cloud"): <https://cloudscape.design/>

Difficult to describe, a personal website/project, espousing some kind of “design philosophy”:
<https://berkeleygraphics.com/>

Extract:

```text
Emergent over prescribed aesthetics.
Expose state and inner workings.
Dense, not sparse.
Explicit is better than implicit.
Regiment functionalism.
Performance is design.
Verbosity over opaqueness.
Ignore design trends. Timeless and unfashionable.
Flat, not hierarchical.
Diametrically opposite of minimalism. As complex as it needs to be.
Driven by specifications and datasheets.
Beauty emerges automatically without deliberation.
Do not infantilize users.
```

Figma Dev: <https://www.figma.com/blog/introducing-dev-mode/>

Cool illustrated guide to DOM events: <Lhttps://domevents.dev/>

"Small laboratory of fine UI": <https://www.uilabs.dev/>

Color space design (Oklab): <https://bottosson.github.io/posts/oklab/>

"The Colour Science Precis is a set of posters designed for the computer-generated imagery artist": <https://github.com/colour-science/colour-science-precis>

"This paper presents an introduction to the color pipelines behind modern feature-film visual-effects and animation": <https://cinematiccolor.org/>

Monospace design experiment: <https://owickstrom.github.io/the-monospace-web/>

The "GPU handbook" (also an interesting design experiment): <https://modal.com/gpu-glossary>

Dax / SST OpenAUTH project (another nice design experiment): 

- <https://openauth.js.org/>
- <https://x.com/thdxr/status/1866197014314131772>

The Rive app:
<https://rive.app/>

Really simple + performant landing page for Planetscale (accessed 31/10/24):
<https://planetscale.com/>

### Viz

<https://observablehq.com/>

TanStack / TanStack Table recommends this as an all-in-one, batteries-included table lib:

<https://www.ag-grid.com/>

### Misc (TODO: Categorize)

Enzo type-checking library:
[unread] <https://kaleidawave.github.io/posts/introducing-ezno/>

Choose "boring" technology (TODO: move this to "philosophy"-esque section):
<https://boringtechnology.club/>

### Multiplayer / CRDT / Live Collab

Open-source framework:
<https://partykit.io/>

CRDT resources:
<https://crdt.tech/resources>

Good tweet + replies on the topic:
<https://x.com/vivekgalatage/status/1840358074114035749>

That ^ tweet links to these guides (good animations):
<https://madebyevan.com/algos/>

CRDT talk ("Consistency without consensus in production systems" by Peter Bourgon):
<https://www.youtube.com/watch?v=em9zLzM8O7c>

## Backend

### Architecture

Figma DB scaling:
[unread] <https://www.figma.com/blog/how-figma-scaled-to-multiple-databases/>

### Data Versioning

Git for data:
<https://www.dolthub.com/>

Git for data-science:
<https://dvc.org/>

Terminus DB:
<https://terminusdb.com/>

### Database General

Astro's offering: <https://astro.build/db/>

Kysely typesafe SQL-query builder (not an ORM): <https://kysely.dev/>

"Managed Duck-DB-in-the-cloud": <https://motherduck.com/>

Google "Pipe Syntax in SQL" experiment: https://research.google/pubs/sql-has-problems-we-can-fix-them-pipe-syntax-in-sql/

Related (and PQL insipiration), PRQL: https://prql-lang.org/

Oriole DB ("OrioleDB: The next-generation storage engine for PostgreSQL"): <https://www.orioledb.com/docs>

### DB Migrations

Schema migrations in PlanetScale:
<https://planetscale.com/docs/devops/declarative-schema-migrations>

Prisma migration mental model:
<https://www.prisma.io/docs/concepts/components/prisma-migrate/mental-model>

Prisma / PlanetScale migration integration:
<https://planetscale.com/docs/prisma/automatic-prisma-migrations>

## Hosting

Good guide to hosting options: <https://getdeploying.com/>

SST (doesn't really belong here anymore, this is IaC or deployment/dev tooling): <https://sst.dev/>

"Coolify is an all-in one PaaS that helps you to self-host your own applications, databases or services (like Wordpress, Plausible Analytics, Ghost) without managing your servers and all the complexity that comes with it, it is also known as an open-source & self-hostable Heroku / Netlify / Vercel alternative.": <https://coolify.io/>

## Programming Language Design and Tooling

Anders Hejlsberg and Guido van Rossum:
[unread] <https://www.youtube.com/watch?v=sBVYn0cIlWM>

Arguments against decorators:
<https://www.reddit.com/r/typescript/comments/w772vv/is_anyone_against_using_decorators/>

Technical dimensions of programming systems:
<https://tomasp.net/techdims/>

Zig (what Bun is written in) tutorial:
<https://www.openmymind.net/learning_zig/>

A newer (more betterer?) tutorial from https://x.com/PedroPark9:
<https://pedropark99.github.io/zig-book/>

The Language Server Protocol (TODO: better place for this link):
<https://microsoft.github.io/language-server-protocol/>
^ linked from above, this TypeScript language definition tool:
<https://github.com/eclipse-langium/langium>

LLVM Tutorial(s):
<https://llvm.org/docs/tutorial/>

## State Management

pmndrs collective projects:

- <https://github.com/pmndrs/zustand>
- <https://github.com/pmndrs/jotai>
- <https://github.com/pmndrs/valtio>

Update from `@dai_shi` on the future (considering big changes to React internals) of the above libraries:

```text
So, my current prediction (don't take it seriously yet as we don't know) are:
- react-tracked will be deprecated
- zustand won't be used as much, neither will use-context-selector
- jotai will still play its role
- valtio will be less attractive, but we'll try our best
```

XState and related:

- <https://stately.ai/>
- <https://xstate.js.org/>

Zustand URL middleware (move state in and out of URL query param):
<https://gist.github.com/tannerlinsley/0ffe9dbf87a6e1dcb88e529a1941c7e5>

## Testing

Artem Zakharchenko (msw.js) articles:

- <https://www.epicweb.dev/the-true-purpose-of-testing>
- <https://www.epicweb.dev/the-golden-rule-of-assertions>

Kent Dodds articles on testing (i.e. React Testing Framework):

- <https://kentcdodds.com/blog/common-mistakes-with-react-testing-library>

Vitest ("Vite-native", shared config): <https://vitest.dev/guide/comparisons.html>

## Culture

Netflix culture (may have been different when it was first published!): <https://jobs.netflix.com/culture>

"Stevey's Google Platforms Rant" (includes the "Bezos memo"): <https://gist.github.com/chitchcock/1281611>

## Estimation and Story Pointing

Actually very good discussion of "Agile", and a guide to what it is / should be / could be:
<https://www.atlassian.com/agile/manifesto>

[read] #NoEstimates (Allen Holub):
<https://www.youtube.com/watch?v=QVBlnCTu9Ms>

[read] <https://ronjeffries.com/articles/019-01ff/story-points/Index.html>

[unread] <https://mdalmijn.com/how-story-points-turned-to-the-dark-side/>

[list] <https://ronjeffries.com/categories/estimation>

## Backlog Management and Todo Lists

[unread] <https://github.com/todotxt/todo.txt>

Todo+ Visual Studio Code Extension (not todo.txt format):
<https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-todo-plus>

## Good Apps

Finance tool, "Fey offers a streamlined view of real-time market data, effortlessly giving you the big picture on your favorite companies.": <https://www.fey.com/>

Developer monetization platform: <https://polar.sh/>

## Good Developer Blogs

Artem Zakharchenko (MSW.js, testing): <https://kettanaito.com/blog>

Josh Comeau (frontend, css, React): <https://www.joshwcomeau.com/>

From above:

- "Why React Re-Renders": <https://www.joshwcomeau.com/react/why-react-re-renders/>

Marc Brooker @ AWS: <https://brooker.co.za/blog/>

From above:

- "It’s About Time!": <https://brooker.co.za/blog/2023/11/27/about-time.html>
- "Learning to build distributed systems": <https://brooker.co.za/blog/2019/04/03/learning.html>
- "DSQL Vignette: Aurora DSQL, and A Personal Story": <https://brooker.co.za/blog/2024/12/03/aurora-dsql.html>

<https://echoesofsomewhere.com/category/devblog/>

Martin Fowler: <https://martinfowler.com/>

From above:

- <https://martinfowler.com/bliki/TeamTopologies.html>
- <https://martinfowler.com/eaaDev/timeNarrative.html>

<https://www.nexxel.dev/>

<https://laughingmeme.org/>

The Grug Brained Developer: <https://grugbrain.dev/>

From above:

- <https://www.dreamsongs.com/WorseIsBetter.html>
- <https://www.dreamsongs.com/Files/worse-is-worse.pdf>
- <https://www.dreamsongs.com/Files/IsWorseReallyBetter.pdf>
- <https://www.goodreads.com/en/book/show/39996759-a-philosophy-of-software-design>

Recommended reading from the htmx site: <https://htmx.org/essays/>
Related to one of the oldest essays in that list: <https://www.theatlantic.com/magazine/archive/1945/07/as-we-may-think/303881/>

Shawn Wang: <https://www.swyx.io/>

Dan Abramov: <https://overreacted.io/>

List of links to list of links: 
- <https://github.com/charlax/professional-programming>
- https://github.com/donnemartin/system-design-primer
- https://github.com/kilimchoi/engineering-blogs
- https://github.com/ByteByteGoHq/system-design-101
- https://github.com/yangshun/front-end-interview-handbook
- https://github.com/yangshun/tech-interview-handbook
- https://github.com/kamranahmedse/developer-roadmap

## AI / Artificial Intelligence

Structured output in ChatGPT: <https://openai.com/index/introducing-structured-outputs-in-the-api/>

## The Java Challenge

Sprint start:
<https://start.spring.io/>

My full spec for the challenge:
<https://claude.ai/chat/65b84490-14c6-4144-ad54-72c578946118>

## Local-first

[https://www.powersync.com/](https://www.powersync.com/)

[https://jazz.tools/](https://jazz.tools/)

[https://electric-sql.com/](https://electric-sql.com/) (and [https://next.electric-sql.com/](https://next.electric-sql.com/))

[https://replicache.dev/](https://replicache.dev/)

[https://zerosync.dev/](https://zerosync.dev/) (from Replicache devs, replacing [Reflect](https://reflect.net/))

## Data Analytics

Data frames:

- Pandas: <https://github.com/pandas-dev/pandas/blob/v2.2.2/pandas/core/frame.py#L509-L12664>
- R: <https://www.rdocumentation.org/packages/base/versions/3.6.2/topics/data.frame>

DuckDB Version 1 announcement: <https://duckdb.org/2024/06/03/announcing-duckdb-100>

Jon's Excel Charts and Tutorials: <https://peltiertech.com/Excel/Charts/ChartIndex.html>

## Books

- <https://www.amazon.co.uk/Black-Box-Thinking-Surprising-Success/dp/1473613779>
- <https://www.amazon.co.uk/Checklist-Manifesto-Things-Right-Gawande/dp/1846683149>

## Uncategorized

List of personal portfolio sites (twitter threads): <https://x.com/pilcrowonpaper/status/1852245786723258468>

[unread] [list] <https://iq.opengenus.org/rpc-vs-rest/#:~:text=1.-,Differences%20between%20RPC%20and%20REST,supports%20GET%20and%20POST%20requests>.

"Using lightweight formal methods to validate a key-value storage node in Amazon S3": <https://www.amazon.science/publications/using-lightweight-formal-methods-to-validate-a-key-value-storage-node-in-amazon-s3>

Hasen Judi's "manifesto" (Grug/US Graphics Company - esque): <https://x.com/Hasen_Judi/status/1781698942935379975>

Someone working on interesting CRDT applications:
<https://twitter.com/JungleSilicon>

DataDog outage analysis:
[unread] <https://newsletter.pragmaticengineer.com/p/inside-the-datadog-outage>

UploadThing from Ping.gg:
<https://github.com/pingdotgg/uploadthing>

Steve Jobs on marketing:
[unread] <https://twitter.com/LinusEkenstam/status/1662105536165183489>

Nice Cuphead-style animations:

- <https://twitter.com/TonyBabel>
- <https://superrare.com/tonybabel>

Very weird but probably very clever “visual coding” system/UI: <https://github.com/samuelmtimbo/unit>

Conversation with Anders about checked exceptions: <https://www.artima.com/articles/the-trouble-with-checked-exceptions>

Dan Abramov / Bluesky ATProto: <https://atproto.com/>

## Business

Dax's philosophy underpinning SST's business model: <https://x.com/thdxr/status/1830990051322237260>

## Good Courses / Instructional Videos

"Learn how to build modern user interfaces for the web": <https://buildui.com/>

"Next.js App Router Authentication (Sessions, Cookies, JWTs)", by leerob@vercel: <https://www.youtube.com/watch?v=DJvM2lSPn6w>

"Mastering Postgres is an in-depth video course by database educator Aaron Francis , in partnership with , the fully-managed PostgreSQL database platform.": <https://masteringpostgres.com/>

## Example of "Good" Documentation

Stripe: long recognized as setting the bar for great API documentation:
<https://stripe.com/docs/api>

Twilio:
<https://www.twilio.com/docs/usage/api>

Dropbox:
<https://www.dropbox.com/developers/documentation>

GitHub:
<https://docs.github.com/en/rest/guides/getting-started-with-the-rest-api>

UK Government Guide:
<https://www.gov.uk/guidance/how-to-document-apis>

React Beta Docs (in particular tutorial and interactive elements):
<https://beta.reactjs.org/>

Plain English Campaign Guide (not an API, but good guidance for written communication):
<https://www.plainenglish.co.uk/files/howto.pdf>

Google Developer Documentation Guidelines:
<https://developers.google.com/style/highlights>

General guidance:
<https://nordicapis.com/7-items-no-api-documentation-can-live-without/>

Non-api docs:
<https://docs.planetscale.com/>

## Not Code

<https://worksinprogress.co/issue/why-britain-doesnt-build>
<https://ukpersonal.finance/index-funds/>
<https://gwern.net/bitcoin-is-worse-is-better>

Camper van listing: <https://www.truckcamperadventure.com/truck-camper-buyers-guide/>

Quebec campers:

- [<https://eboudreaultvr.com/>](https://www.lelievremecaniquesport.com/fr/)
- https://www.vr-evolution.ca/fr/
- https://www.roulottehl.com/caravanes-portees
- https://northern-lite.com/canadian-rv-dealers/
