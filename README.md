# orbtr.io/news

News and announcement content for [orbtr.io](https://orbtr.io).

## Structure

- **news.yaml** — Article entries rendered on the orbtr.io news page. Each article has a title, date, tag, description, optional highlights, and call-to-action buttons.

## Adding an Article

Append a new entry to `articles` in `news.yaml`:

```yaml
- title: "Article Title"
  date: "YYYY-MM-DD"
  tag: "Release"          # Release | Update | Security | Community
  featured: false
  description: >
    Short description of the announcement.
  highlights:
    - "Bullet point 1"
    - "Bullet point 2"
  actions:
    - text: "Learn More"
      url: "/blog/article-slug"
      style: "primary"    # primary | ghost
```

## Ownership

Maintained by the ORBTR team. Content is consumed by the orbtr.io static site build.
