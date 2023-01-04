# alias-ko
Public repository of cool aliases that you can `curl` or `wget` and be ready to go on a new installation.
> inspired by this video  
>  
> <a href="https://youtu.be/n70IdVvWrzE"><img src="https://i.ytimg.com/vi/n70IdVvWrzE/hqdefault.jpg"/></a>  
> created by [@metalx1000](https://github.com/metalx1000)

## Motivation

I want a memorable / simple `URL` to a file that I download, it contains `aliases` that the community over at [KO's YouTUBE Channel](https://www.youtube.com/@DigitalMetal) can colaborate on, by contributing their favourite aliases.

## How it works

1. create a [`PR`](https://github.com/realvorl/alias-ko/pulls) on this repository & with your favourite `alias(es)`   
1. wait for the next release ( every two weeks - will be automated by GitHub actions )
3. use this URL: `https://bit.ly/ko-alias` to download the aliases.
```bash
# example with cURL for BASH
curl -L https://bit.ly/ko-alias >> ~/.bash_aliases
source ~/.bash_aliases
``` 
4. request an alias by using the [`issues`](https://github.com/realvorl/alias-ko/issues) if you think it is useful but don't know how to implement it yourself
