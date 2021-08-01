<div>
  <h1 align="center">ORKUT</h1> </br>
  <h9 align="center"><em>Social media cloning fullstack.</em></h9> 
</div>

### To do

- [x] ReactJs 
- [-] NextJs 
- [-] SQL 

<div>
  <h1 align="center">PROTOTYPE</h1> </br>
  <h9 align="center"><em>x</em></h9> 
</div>
---

    v 0.0.0

<h9 align="center">
  <em>...<em>
</h9>

<div>
<image align="center" src="./src/screen/screen-v0.png"></image>
</div>

<div>
  <h1><img src="./src/versions/screen-v0.png"/></h1>
</div>

---

<div>
  <h1 align="center">DOCUMENTATION</h1>
</div>

# #NPM LINES

    $ yarn dev
.

    $ yarn run 

---



<details>
<summary>Click to expand workaround example</summary>
<br />

**components/StyledLink.js**

```javascript
import Link from 'next/link'
import styled from 'styled-components'

const StyledLink = ({ as, children, className, href }) => (
  <Link href={href} as={as} passHref>
    <a className={className}>{children}</a>
  </Link>
)

export default styled(StyledLink)`
  color: #0075e0;
  text-decoration: none;
  transition: all 0.2s ease-in-out;

  &:hover {
    color: #40a9ff;
  }

  &:focus {
    color: #40a9ff;
    outline: none;
    border: 0;
  }
`
```

**pages/index.js**

```javascript
import StyledLink from '../components/StyledLink'

export default () => (
  <StyledLink href="/post/[pid]" forwardedAs="/post/abc">
    First post
  </StyledLink>
)
```

</details>
