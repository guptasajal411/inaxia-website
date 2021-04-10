# inaxia
A fully responsive site for all inaxia guild members. I made this using HTML, CSS and Bootstrap!

You can view this site [**here.**](https://guptasajal411.github.io/inaxia-website/)

## Contributing Guide
If you are a member of inaxia, add your card to this site by following these steps!

1. Fork this repository.
2. Clone the forked repository on your local system.
3. Add your profile image inside the "images" folder. Rename the image to your own name.jpg
4. Paste this code above the `<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ PASTE YOUR CODE ABOVE THIS LINE ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->` line:
```
            <div class="col-sm-12 col-md-6 col-lg-4 col-xl-3 mb-4">
                <div class="card cardHere ">
                    <img class="card-img-top" src="images/YOUR PROFILE IMAGE NAME.jpg" alt="Card image cap">
                    <div class="card-body">
                        <h5 class="card-title">YOUR NAME</h5>
                        <p class="card-text">SHORT BIO ABOUT YOURSELF</p>
                        <a href="LINK TO YOUR GITHUB PROFILE" class="btn btn-primary personalised-btn" ><i class="fab fa-github fa-lg"></i></a>
                        <a href="LINK TO YOUR LINKEDIN PROFILE" class="btn btn-primary personalised-btn" ><i class="fab fa-linkedin fa-lg"></i></a>
                    </div>
                </div>
            </div>

            
```
5. Stage your changes by `git add -A`
6. Commit your changes by `git commit -m "Add YOUR NAME card to the site"`
7. Push your changes to your forked repository by `git push origin main`
8. Create a pull request and I'll merge your card to the site!
