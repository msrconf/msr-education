
# Local use

Get bundler:

    gem install --user bundler
    # add the ruby bin to your PATH var
    # e.g.
    # export PATH=${HOME}/.gem/ruby/2.5.0/bin${PATH:+:${PATH}}
    bundle config bin  ${HOME}/.gem/ruby/2.5.0/bin
    bundle config path ${HOME}/.gem/ruby/2.5.0/

Then in the root of this repo type:

    bundler update

Lots of horrible and horrendous ruby depdencies will be installed.
