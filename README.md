# Hugo GitHub Issue #11221

Details: <https://github.com/gohugoio/hugo/issues/11221>

Description: `hugo mod` does not copy hugo.toml to _vendor

## Instructions

Clone this branch of the repository and build the site.

```bash
git clone https://github.com/markdumay/hugo-mod-test-site.git
cd hugo-mod-test-site
hugo 
hugo mod vendor
tree _vendor
```
