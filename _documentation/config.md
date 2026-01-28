- dependencies
    ruby
        ruby --version
    gem install bundler
        gem update --system 4.0.4
        gem --version
        bundler --version
    node --version
    gem install jekyll bundler
    jekyll --version
    bundle install




- development

jekyll serve -l -H localhost 
    çalışmadı
        gem file değiştirdik
        sonra da aha
            bash
            bundle clean --force
            bundle install
            bundle exec jekyll serve
                üstteki kullanılacak
            
