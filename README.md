# competitor-library-supplements-1

Public media for the Growth Dept competitor library (https://growthdept.ai/library), vertical: supplements.
Files are served from `https://raw.githubusercontent.com/holdenjrussell/competitor-library-supplements-1/main/<path>`, so they render in AI
chats, MCP tools and web pages without sign-in.

Only public marketing goes here: ads from public ad libraries, marketing emails sent to subscribers, and public
landing pages, each checked before it is pushed. Never a Growth Dept client's own creative, and nothing that says
which client watches which brand.

| Path | Contents |
|---|---|
| `<brand>/ads/<yyyy>/<sha16>.mp4` | Ad video, web size (H.264, at most 960 px and 120 s) |
| `<brand>/ads/<yyyy>/<sha16>-poster.jpg` | Its poster frame |
| `<brand>/ads/<yyyy>/<sha16>.jpg` | Ad image, at most 1080 px wide |
| `<brand>/emails/<id>.jpg` | Rendered marketing email |
| `<brand>/lps/<id>.jpg` | Landing page, desktop |

File names are content hashes or the library's public ids, so URLs never change.
