# Awesome TikTok [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for TikTok API integrations, video processing automation, research scraping toolkits, analytics extraction, live streaming software, and developer tooling.

TikTok is a short-form video platform driven by recommendation algorithms, mobile content creation, live streaming, and social commerce APIs. Programmatic access to TikTok enables content publishing, user engagement metrics tracking, trend discovery, video processing pipelines, and data scraping for computational social science. This list is intended for social media developers, automation engineers, digital content creators, media researchers, and growth analytics leads.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official APIs & SDKs](#official-apis--sdks)
- [Scraping & Data Extraction](#scraping--data-extraction)
- [Video Processing & Editing Automation](#video-processing--editing-automation)
- [Live Streaming & WebSockets](#live-streaming--websockets)
  - [Live Stream Connectors](#live-stream-connectors)
  - [Bot & Event Frameworks](#bot--event-frameworks)
- [Research & Social Analytics](#research--social-analytics)
- [Related Awesome Lists](#related-awesome-lists)

## Official APIs & SDKs

Official developer platform documentation, OAuth authentication protocols, and REST API suites.

- [TikTok Content Posting API](https://developers.tiktok.com/) — Official API suite for uploading, scheduling, and publishing video content directly to user profiles programmatically.
- [TikTok Display API](https://developers.tiktok.com/) — REST API granting access to user profile information, public video lists, and basic account analytics via OAuth2.
- [TikTok Commercial Content API](https://developers.tiktok.com/) — Official API accessing commercial video archives and ad library transparency metadata.
- [TikTok Login Kit](https://developers.tiktok.com/) — OAuth2 integration enabling user authentication and single sign-on (SSO) with TikTok credentials.

## Scraping & Data Extraction

Open-source scrapers, headless browser automation scripts, and API wrappers for extracting video metadata and user profiles.

- [TikTok-Api](https://github.com/davidteather/TikTok-Api) — Unofficial Python wrapper for retrieving user data, trending videos, hashtags, and music tracks via Playwright.
- [TikTokScraper](https://github.com/drawrowfly/tiktok-scraper) — Node.js scraping utility for downloading posts, user feeds, audio tracks, and batch metadata.
- [TikTok-Downloader](https://github.com/yt-dlp/yt-dlp) — Integrated video extraction engine within `yt-dlp` supporting watermark-free video downloads and audio extractions.
- [TikTokPy](https://github.com/tik-tok-py/TikTokPy) — Python automation framework powered by Asyncio and Playwright for managing user interactions.

## Video Processing & Editing Automation

Programmatic video assembly, automatic subtitle generation, dynamic resizing, and rendering engines.

- [Remotion](https://github.com/remotion-dev/remotion) — React-based framework for generating short-form 9:16 vertical video content programmatically.
- [MoviePy](https://github.com/Zulko/moviepy) — Scriptable Python library for video editing, cutting, caption insertion, and format conversion.
- [Auto-Subtitles (Whisper)](https://github.com/openai/whisper) — OpenAI's speech recognition model widely utilized for generating viral, high-accuracy subtitle overlays.
- [FFmpeg TikTok Templates](https://github.com/FFmpeg/FFmpeg) — Command-line scripts for scaling, cropping 16:9 media to 9:16 vertical formats, and burning subtitles.

## Live Streaming & WebSockets

Real-time interaction engines, live chat connection libraries, and stream listener event loops.

### Live Stream Connectors

- [TikTokLive](https://github.com/isaackogan/TikTokLive) — Python library for connecting to ongoing TikTok Live broadcasts via WebSocket protocols to listen for chat comments and gifts.
- [TikTok-Live-Connector](https://github.com/zerodytrash/TikTok-Live-Connector) — Node.js package providing real-time events for TikTok Live chats, viewer counts, likes, and digital gifts.

### Bot & Event Frameworks

- [TikTokLive-Java](https://github.com/isaackogan/TikTokLive-Java) — Java library engineered for building real-time interactive bots and stream alerts for live events.
- [TikTok-Live-Streamer](https://github.com/obsproject/obs-studio) — OBS Studio configuration tools and plugins optimized for vertical streaming pipelines.

## Research & Social Analytics

Computational social science toolkits, trend tracking frameworks, and academic research platforms.

- [TikTok Research API Wrapper](https://developers.tiktok.com/products/research-api/) — Official research portal library providing credentialed access to public video, user, and comment data for academic institutions.
- [PyKTok](https://github.com/jepusto/pyktok) — Python library designed for quantitative researchers to collect and parse TikTok video metadata into structured DataFrames.
- [TikTok-Trend-Analysis](https://github.com/social-media-research) — Open analytics pipeline for measuring viral hashtag propagation, audio usage patterns, and engagement metrics.
- [TKMetrics](https://tkmetrics.com/) — Public TikTok account statistics: followers, average views, engagement rate, top videos, hashtags and sounds used.

## Related Awesome Lists

- [Awesome YouTube](https://github.com/brandonhimpfen/awesome-youtube) — Video processing, YouTube Data API, live streaming, and channel automation toolkits.
- [Awesome Open-Source AI Models](https://github.com/brandonhimpfen/awesome-open-source-ai-models) — Multimodal vision-language models, audio transcription engines, and generative pipelines.
- [Awesome JavaScript](https://github.com/brandonhimpfen/awesome-javascript) — Web runtimes, node automation libraries, and asynchronous event pipelines.
- [Awesome Python](https://github.com/brandonhimpfen/awesome-python) — Data scraping frameworks, media processing, and machine learning toolkits.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
