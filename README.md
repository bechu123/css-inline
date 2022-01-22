# css-inline
This projects tells how to apply CSS in the html file itself

# How to build ?
1. Check out repo
2. Run "docker build -t my-css-test-image .

# How to run ?
1. docker run -d -p 8080:80 --mount type=bind,src=<abs path of html>,dst=/usr/share/nginx/html/ -name my-css-test1 my-css-test-image
2. curl http:/127.0.0.1:8080
3. docker restart my-css-test1 to reflect the changes in html