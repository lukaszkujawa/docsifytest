# Features

## Markdown

- Parent1
  - Child1
  - Child2
  - Child3
- Parent2

## Syntax Highlight

HTML
```html
<script src="//unpkg.com/docsify/lib/docsify.min.js"></script>
<script src="//unpkg.com/prismjs/components/prism-bash.min.js"></script>
<script src="//unpkg.com/prismjs/components/prism-haskell.min.js"></script>
```

Haskell
```haskell
import Network.HTTP.Conduit
import Control.Monad.IO.Class (liftIO)

main = withManager $ \manager -> do
    request <- parseUrl "http://www.winsoft.sk"
    liftIO $ print request
    response <- httpLbs request manager
    liftIO $ print response
```
