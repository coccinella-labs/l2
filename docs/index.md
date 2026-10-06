# Friday Gemini AI

A Ruby interface to Google's Gemini AI models, designed for simplicity, security, and power.

## Quick Start

Install the gem from git (it is not published to RubyGems):

```bash
gem install specific_install
gem specific_install -l https://github.com/coccinella-labs/l2
```

Set your API key:

```bash
export GEMINI_API_KEY="your-api-key-here"
```

Generate text:

```ruby
require 'friday_gemini_ai'

client = GeminiAI::Client.new
response = client.generate_text("Hello, Gemini!")
puts response
```

## HarperBot

[HarperBot](reference/harperbot.md) automates code reviews using Gemini AI, analyzing PRs and providing feedback.

## Documentation

- [Quick Start](start/quickstart.md)
- [API Reference](reference/api.md)
- [HarperBot](reference/harperbot.md)
- [Guides](guides/community.md)
- [Testing](reference/testing.md)

## Links

- [Issues](https://github.com/coccinella-labs/l2/issues)
- [Security](https://github.com/coccinella-labs/l2/blob/main/.github/SECURITY.md)
- [License](https://github.com/coccinella-labs/l2/blob/main/LICENSE)
