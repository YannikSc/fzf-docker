Inspired by a contribution of calbertts in [this fzf issue](https://github.com/junegunn/fzf/issues/760).

# Dependencies

- [fzf](https://github.com/junegunn/fzf)
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

# Installation

Clone the repo in `.oh-my-zsh/plugins/fzf-docker`

```bash
git clone https://github.com/pierpo/fzf-docker ~/.oh-my-zsh/plugins/fzf-docker
```

Then add the plugin to your `.zshrc`

```bash
# In your .zshrc
plugins=(... fzf-docker ...)
```

# Usage

If you don't like the `**` prefix (which is a fzf thing), you may change it in your `zshrc`:

```bash
export FZF_COMPLETION_TRIGGER='**'
```

I personally put `,` instead :wink:

## Command list

```bash
docker **<TAB>
```

## Remove images

```bash
docker rmi **<TAB>
```

## Start containers

```bash
docker start **<TAB>
```

## Stop containers

```bash
docker stop **<TAB>
```

## Remove containers

```bash
docker rm **<TAB>
```
