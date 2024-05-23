# README

Source API docs:
https://api.f2pool.com/v2/doc/en.html

Converted to markdown using: 
https://github.com/suntong/html2md?tab=readme-ov-file#downloadinstall-binaries
`html2md -i https://api.f2pool.com/v2/doc/en.html -T -G > f2-pool.md`
Use this to diff for changes?

Using GitHub Copilot GPT thing to generate:
`f2-openapi.yml`

Copilot prompts when highlighting sections of f2-pool.md
> generate the open api path for this, don't generate the paths field and add a default response that is an "Error response" and has an application/json content with an object schema with integer field "code" and string field "msg"

> generate openapi component schema for this, don't out "components" or "schema"

Then go use:
https://openapi-generator.tech/
to make your lib