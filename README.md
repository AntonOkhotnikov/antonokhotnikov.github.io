Anton Okhotnikov's personal webpage repository.

### Development

1. Install *ruby-2.7.6* with [rvm](https://github.com/rvm/rvm)
```bash
rvm install 2.7.6
```

2. Install `bundler`:
```bash
gem install bundle
```

3. Install `Gemfile` dependencies:
```bash
cd <path_to_this_repo_root>
bundle install
```

4. Run page locally:
```bash
bundle exec jekyll serve
```

5. Set your git repo Pages setting in GitHub to `Deploy from a branch`

6. After `git commit` and `git push` to **master** branch GitHub Page is deployed automatically
