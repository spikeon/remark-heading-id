# remark-heading-id

> The remark plugin for supporting [custom heading id](https://www.markdownguide.org/extended-syntax/#heading-ids) and Default Id

### Custom Heading Input

```markdown
### My Great Heading {#custom-id}
```

### Custom Heading Output

```html
<h3 id="custom-id">My Great Heading</h3>
```

### Default Heading Input

```markdown
### My Great Heading
```

### Default Heading Output

```html
<h3 id="my-great-heading">My Great Heading</h3>
```

## Contributing

- Fork it!
- Create your new branch:  
  `git checkout -b feature-new` or `git checkout -b fix-which-bug`
- Start your magic work now
- Make sure npm test passes
- Commit your changes:  
  `git commit -am 'feat: some description (close #123)'` or `git commit -am 'fix: some description (fix #123)'`
- Push to the branch: `git push`
- Submit a pull request :)

## Authors

This library is written and maintained by spikeon, <a href="mailto:spikeon@gmail.com">moyuyc95@gmail.com</a>.  
Based on work by imcuttle, <a href="mailto:moyuyc95@gmail.com">moyuyc95@gmail.com</a>.

## License

MIT - [spikeon](https://github.com/spikeon) 🐟
