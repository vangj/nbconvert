# nbconvert

## Installation

Simply install [WP Pusher](https://wppusher.com/) by downloading and installing the package from a zip file then add my wordpress plugin from my git repo! by adding the uri into the git plugin installer (ghandic/nbconvert)


## How it works

Simply add a shortcode and a url to the notebook file

[nbconvert url="https://github.com/python-visualization/folium/blob/master/examples/CheckZorder.ipynb"]

PHP then sends the url to an nbviewer API that will convert the ipynb file to html

## Next steps

### CSS
- Some more work may be needed to make the html snippet to display like a an ipynb
- We may need to make some tests to check that it is working on different themes?

