# jQuery Image Maker
## Image maker

> **JQuery Image Maker responsive plugin enable you to add a custom resizable texts to image in addition to merge images and Draw. It based on HTML5 canvas. **

## Demo & Examples

[https://www.tolastbit.com/apps/meme-generator](https://www.tolastbit.com/apps/meme-generator)

## Depends libraries:
 *  jquery
 *  jquery.ui
 *  jqueryui-touch-punch(optional for mobile)

## Example Usage

## Using JQuery maker

Just follow these simple steps in order to enable Image Maker to your app:

1. Include jQuery and jQuery UI and jQuery UI Touch Punch on your page.

    ```html
    <script src="https://code.jquery.com/jquery-1.12.4.js"></script>
    <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jqueryui-touch-punch/0.2.2/jquery.ui.touch-punch.min.js"></script>
    ```
    Note: You can skip the include of jqueryui-touch-punch plugin for desktop use only
    
2. Download imageMaker then add imageMaker.js and imageMaker.css.

    ```html
    <script src="imageMake.js"></script>
    <link rel="stylesheet" href="imageMake.css">
    ```

3. Add in the body of the page html the main element of Image Maker.

    ```html
    <div id="imageMaker1"></div>
    ```
4. Enable the Image Maker by add the following js code
    ```js
    $('#imageMaker1').imageMaker()
    ```    
 # Settings
| Option name | Description | type | Default |
| :---         |     :---:      |     :---: |     ---: |
| templates   | You can predefine images that used as template. So It's array of object that contains url and title of predefined templated   | [{url:'','title':''},]    |[] |
| template_thumbnail_width     | Width of predefined template       |   integer   | 50 |
| template_thumbnail_height     | Height of predefined template       |   integer   | 50 |
| merge_images   | You can predefine images to merge with the template. so It's array of object that contains url and title of predefined merges Images   | [{url:'','title':''}]    | []|

_Tested on iPad, iPhone, Android and other touch-enabled mobile devices._