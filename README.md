# My-Site-
mkdir my-site
cd my-site
git init
echo "<!DOCTYPE html>
<html>
  <head><title>My Portfolio</title></head>
  <body>
    <h1>Welcome to My Work!</h1>
    <p>Contact me at <!--email_off-->23f3003731@ds.study.iitm.ac.in<!--/email_off--></p>
  </body>
</html>" > index.html

git add index.html
git commit -m "feat(pages): initial commit"
git branch -M main
git remote add origin https://github.com/reneenor13/my-site.git
git push -u origin main
