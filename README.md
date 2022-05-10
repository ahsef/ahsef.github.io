#run jekyll using docker

docker run --rm --volume="$PWD:/srv/jekyll" -p 80:4000 -it jekyll/jekyll:4.2.0 jekyll serve --watch --drafts
