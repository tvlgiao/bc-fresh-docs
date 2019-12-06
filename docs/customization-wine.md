<div ng-app="app">
  <!-- Modal -->
  <div class="modal fade" id="lightbulbs_banner_1" tabindex="-1" role="dialog" aria-labelledby="lightbulbs_banner_1_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="lightbulbs_banner_1_label">Code Generator: Lightbulbs Banner Style 1</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="form-group">
              <label for="lightbulbs_banner_1_background_img">Background Image URL:</label>
              <input ng-model="background_img" type="text" class="form-control" id="lightbulbs_banner_1_background_img" ng-init="background_img='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-bg.jpg'">
            </div>
            <div class="panel-group" id="lightbulbs_banner_1_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_1_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_1_accordion" href="#lightbulbs_banner_1_item1_collapse" aria-expanded="true" aria-controls="lightbulbs_banner_1_item1_collapse">
                      Row 1
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_1_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="lightbulbs_banner_1_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_heading">Heading:</label>
                      <input ng-model="row1_heading" type="text" class="form-control" id="lightbulbs_banner_1_row1_heading" ng-init="row1_heading='Ceiling <br>Lights'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_desc">Desc:</label>
                      <input ng-model="row1_desc" type="text" class="form-control" id="lightbulbs_banner_1_row1_desc"
                      ng-init="row1_desc='Add some shine with a ceiling lights!'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_link">Button URL:</label>
                      <input ng-model="row1_link" type="text" class="form-control" id="lightbulbs_banner_1_row1_link"
                      ng-init="row1_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_button_text">Button Text:</label>
                      <input ng-model="row1_button_text" type="text" class="form-control" id="lightbulbs_banner_1_row1_button_text"
                      ng-init="row1_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_image_1">Image :</label>
                      <input ng-model="row1_image_1" type="text" class="form-control" id="lightbulbs_banner_1_row1_image_1" ng-init="row1_image_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-1.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row1_youtube_embed">Youtube Embed:</label>
                      <input ng-model="row1_youtube_embed" type="text" class="form-control" id="lightbulbs_banner_1_row1_youtube_embed" ng-init="row1_youtube_embed='<iframe width=&quot;560&quot; height=&quot;315&quot; src=&quot;https://www.youtube.com/embed/-vtBgNxMyZI&quot; frameborder=&quot;0&quot; allow=&quot;autoplay; encrypted-media&quot; allowfullscreen></iframe>'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_1_item2_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_1_accordion" href="#lightbulbs_banner_1_item2_collapse" aria-expanded="false" aria-controls="lightbulbs_banner_1_item2_collapse">
                      Row 2
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_1_item2_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="lightbulbs_banner_1_item2_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_heading">Heading:</label>
                      <input ng-model="row2_heading" type="text" class="form-control" id="lightbulbs_banner_1_row2_heading" ng-init="row2_heading='Floor &amp; <br>Table Lamps'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_desc">Desc:</label>
                      <input ng-model="row2_desc" type="text" class="form-control" id="lightbulbs_banner_1_row2_desc"
                      ng-init="row2_desc='Add some shine with a floor lamp!<br> Our modern floor lamps'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_link">Button URL:</label>
                      <input ng-model="row2_link" type="text" class="form-control" id="lightbulbs_banner_1_row2_link"
                      ng-init="row2_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_button_text">Button Text:</label>
                      <input ng-model="row2_button_text" type="text" class="form-control" id="lightbulbs_banner_1_row2_button_text"
                      ng-init="row2_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_image_slider_1">Slider Image 1:</label>
                      <input ng-model="row2_image_slider_1" type="text" class="form-control" id="lightbulbs_banner_1_row2_image_slider_1" ng-init="row2_image_slider_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-2.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_link_slider_1">Image 1 URL:</label>
                      <input ng-model="row2_link_slider_1" type="text" class="form-control" id="lightbulbs_banner_1_row2_link_slider_1"
                      ng-init="row2_link_slider_1='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_image_slider_2">Slider Image 2:</label>
                      <input ng-model="row2_image_slider_2" type="text" class="form-control" id="lightbulbs_banner_1_row2_image_slider_2" ng-init="row2_image_slider_2='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-3.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_link_slider_2">Image 2 URL:</label>
                      <input ng-model="row2_link_slider_2" type="text" class="form-control" id="lightbulbs_banner_1_row2_link_slider_2"
                      ng-init="row2_link_slider_2='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_image_slider_3">Slider Image 3:</label>
                      <input ng-model="row2_image_slider_3" type="text" class="form-control" id="lightbulbs_banner_1_row2_image_slider_3" ng-init="row2_image_slider_3='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-4.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_link_slider_3">Image 3 URL:</label>
                      <input ng-model="row2_link_slider_3" type="text" class="form-control" id="lightbulbs_banner_1_row2_link_slider_3"
                      ng-init="row2_link_slider_3='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_image_slider_4">Slider Image 4:</label>
                      <input ng-model="row2_image_slider_4" type="text" class="form-control" id="lightbulbs_banner_1_row2_image_slider_4" ng-init="row2_image_slider_4='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-5.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row2_link_slider_4">Image 4 URL:</label>
                      <input ng-model="row2_link_slider_4" type="text" class="form-control" id="lightbulbs_banner_1_row2_link_slider_4"
                      ng-init="row2_link_slider_4='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_1_item3_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_1_accordion" href="#lightbulbs_banner_1_item3_collapse" aria-expanded="false" aria-controls="lightbulbs_banner_1_item3_collapse">
                      Row 3
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_1_item3_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="lightbulbs_banner_1_item3_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_heading">Heading:</label>
                      <input ng-model="row3_heading" type="text" class="form-control" id="lightbulbs_banner_1_row3_heading" ng-init="row3_heading='Wall <br>Lights'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_desc">Desc:</label>
                      <input ng-model="row3_desc" type="text" class="form-control" id="lightbulbs_banner_1_row3_desc"
                      ng-init="row3_desc='Add some shine with a ceiling lights!'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_link">Button URL:</label>
                      <input ng-model="row3_link" type="text" class="form-control" id="lightbulbs_banner_1_row3_link"
                      ng-init="row3_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_button_text">Button Text:</label>
                      <input ng-model="row3_button_text" type="text" class="form-control" id="lightbulbs_banner_1_row3_button_text"
                      ng-init="row3_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_image_1">Image 1:</label>
                      <input ng-model="row3_image_1" type="text" class="form-control" id="lightbulbs_banner_1_row3_image_1" ng-init="row3_image_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-6.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_1_row3_image_2">Image 2:</label>
                      <input ng-model="row3_image_2" type="text" class="form-control" id="lightbulbs_banner_1_row3_image_2" ng-init="row3_image_2='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-1-7.png'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/lightbulbs_home_banner1.txt'" compile="true" id="lightbulbs_home_banner1_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#lightbulbs_home_banner1_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #lightbulbs_banner_1 -->
  <!-- Modal -->
  <div class="modal fade" id="lightbulbs_banner_2" tabindex="-1" role="dialog" aria-labelledby="lightbulbs_banner_2_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="lightbulbs_banner_2_label">Code Generator: Lightbulbs Banner Style 2</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="form-group">
              <label for="lightbulbs_banner_2_background_img">Background Image URL:</label>
              <input ng-model="background_img" type="text" class="form-control" id="lightbulbs_banner_2_background_img" ng-init="background_img='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-bg.jpg'">
            </div>
            <div class="panel-group" id="lightbulbs_banner_2_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_2_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_2_accordion" href="#lightbulbs_banner_2_item1_collapse" aria-expanded="true" aria-controls="lightbulbs_banner_2_item1_collapse">
                      Row 1
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_2_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="lightbulbs_banner_2_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row1_heading">Heading:</label>
                      <input ng-model="row1_heading" type="text" class="form-control" id="lightbulbs_banner_2_row1_heading" ng-init="row1_heading='LED Light Bulds'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row1_desc">Desc:</label>
                      <input ng-model="row1_desc" type="text" class="form-control" id="lightbulbs_banner_2_row1_desc"
                      ng-init="row1_desc='Add some shine with a LED light! <br>Our modern LED light'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row1_link">Button URL:</label>
                      <input ng-model="row1_link" type="text" class="form-control" id="lightbulbs_banner_2_row1_link"
                      ng-init="row1_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row1_button_text">Button Text:</label>
                      <input ng-model="row1_button_text" type="text" class="form-control" id="lightbulbs_banner_2_row1_button_text"
                      ng-init="row1_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row1_image_1">Image :</label>
                      <input ng-model="row1_image_1" type="text" class="form-control" id="lightbulbs_banner_2_row1_image_1" ng-init="row1_image_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-1.gif'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_2_item2_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_2_accordion" href="#lightbulbs_banner_2_item2_collapse" aria-expanded="false" aria-controls="lightbulbs_banner_2_item2_collapse">
                      Row 2
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_2_item2_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="lightbulbs_banner_2_item2_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row2_heading">Heading:</label>
                      <input ng-model="row2_heading" type="text" class="form-control" id="lightbulbs_banner_2_row2_heading" ng-init="row2_heading='Outdoor <br>&amp; Landscape'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row2_desc">Desc:</label>
                      <input ng-model="row2_desc" type="text" class="form-control" id="lightbulbs_banner_2_row2_desc"
                      ng-init="row2_desc='Add some shine with a ceiling lights!'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row2_link">Button URL:</label>
                      <input ng-model="row2_link" type="text" class="form-control" id="lightbulbs_banner_2_row2_link"
                      ng-init="row2_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row2_button_text">Button Text:</label>
                      <input ng-model="row2_button_text" type="text" class="form-control" id="lightbulbs_banner_2_row2_button_text"
                      ng-init="row2_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row2_image_1">Image:</label>
                      <input ng-model="row2_image_1" type="text" class="form-control" id="lightbulbs_banner_2_row2_image_1" ng-init="row2_image_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-2.jpg'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="lightbulbs_banner_2_item3_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#lightbulbs_banner_2_accordion" href="#lightbulbs_banner_2_item3_collapse" aria-expanded="false" aria-controls="lightbulbs_banner_2_item3_collapse">
                      Row 3
                    </a>
                  </h4>
                </div>
                <div id="lightbulbs_banner_2_item3_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="lightbulbs_banner_2_item3_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_heading">Heading:</label>
                      <input ng-model="row3_heading" type="text" class="form-control" id="lightbulbs_banner_2_row3_heading" ng-init="row3_heading='Lighting Accessories'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_desc">Desc:</label>
                      <input ng-model="row3_desc" type="text" class="form-control" id="lightbulbs_banner_2_row3_desc"
                      ng-init="row3_desc='Explore brilliant selection of home lighting hardware and accessories  like light bulbs, lamp adapter kits.'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_link">Button URL:</label>
                      <input ng-model="row3_link" type="text" class="form-control" id="lightbulbs_banner_2_row3_link"
                      ng-init="row3_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_button_text">Button Text:</label>
                      <input ng-model="row3_button_text" type="text" class="form-control" id="lightbulbs_banner_2_row3_button_text"
                      ng-init="row3_button_text='Shop Now'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_image_slider_1">Slider Image 1:</label>
                      <input ng-model="row3_image_slider_1" type="text" class="form-control" id="lightbulbs_banner_2_row3_image_slider_1" ng-init="row3_image_slider_1='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-3.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_link_slider_1">Image 1 URL:</label>
                      <input ng-model="row3_link_slider_1" type="text" class="form-control" id="lightbulbs_banner_2_row3_link_slider_1"
                      ng-init="row3_link_slider_1='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_image_slider_2">Slider Image 2:</label>
                      <input ng-model="row3_image_slider_2" type="text" class="form-control" id="lightbulbs_banner_2_row3_image_slider_2" ng-init="row3_image_slider_2='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-4.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_link_slider_2">Image 2 URL:</label>
                      <input ng-model="row3_link_slider_2" type="text" class="form-control" id="lightbulbs_banner_2_row3_link_slider_2"
                      ng-init="row3_link_slider_2='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_image_slider_3">Slider Image 3:</label>
                      <input ng-model="row3_image_slider_3" type="text" class="form-control" id="lightbulbs_banner_2_row3_image_slider_3" ng-init="row3_image_slider_3='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-5.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_link_slider_3">Image 3 URL:</label>
                      <input ng-model="row3_link_slider_3" type="text" class="form-control" id="lightbulbs_banner_2_row3_link_slider_3"
                      ng-init="row3_link_slider_3='#'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_image_slider_4">Slider Image 4:</label>
                      <input ng-model="row3_image_slider_4" type="text" class="form-control" id="lightbulbs_banner_2_row3_image_slider_4" ng-init="row3_image_slider_4='//cdn8.bigcommerce.com/s-3qvmac4a37/product_images/uploaded_images/lightbulbs-banner-section-2-6.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="lightbulbs_banner_2_row3_link_slider_4">Image 4 URL:</label>
                      <input ng-model="row3_link_slider_4" type="text" class="form-control" id="lightbulbs_banner_2_row3_link_slider_4"
                      ng-init="row3_link_slider_4='#'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/lightbulbs_home_banner2.txt'" compile="true" id="lightbulbs_home_banner2_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#lightbulbs_home_banner2_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #lightbulbs_banner_2 -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_home_banner1_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_home_banner1_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_home_banner1_modal_label">Code Generator: Homepage 5 Banners</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_home_banner1_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner1_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_home_banner1_accordion" href="#chiara_home_banner1_item1_collapse" aria-expanded="true" aria-controls="chiara_home_banner1_item1_collapse">
                      Banner 1
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner1_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_home_banner1_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner1_item1_img_bg">Background Image URL:</label>
                      <input ng-model="item1_img_bg" type="text" class="form-control" id="chiara_home_banner1_item1_img_bg" ng-init="item1_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner1.jpg?t=1534872898'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item1_img_fg">Front Image URL:</label>
                      <input ng-model="item1_img_fg" type="text" class="form-control" id="chiara_home_banner1_item1_img_fg" ng-init="item1_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner1a.png?t=1534872899'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item1_alt">Image Alt:</label>
                      <input ng-model="item1_alt" type="text" class="form-control" id="chiara_home_banner1_item1_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item1_link">Link URL:</label>
                      <input ng-model="item1_link" type="text" class="form-control" id="chiara_home_banner1_item1_link">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner1_item2_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner1_accordion" href="#chiara_home_banner1_item2_collapse" aria-expanded="false" aria-controls="chiara_home_banner1_item2_collapse">
                      Banner 2
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner1_item2_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner1_item2_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner1_item2_img_bg">Background Image URL:</label>
                      <input ng-model="item2_img_bg" type="text" class="form-control" id="chiara_home_banner1_item2_img_bg" ng-init="item2_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2.jpg?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item2_img_fg">Front Image URL:</label>
                      <input ng-model="item2_img_fg" type="text" class="form-control" id="chiara_home_banner1_item2_img_fg" ng-init="item2_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2a.png?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item2_alt">Image Alt:</label>
                      <input ng-model="item2_alt" type="text" class="form-control" id="chiara_home_banner1_item2_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item2_link">Link URL:</label>
                      <input ng-model="item2_link" type="text" class="form-control" id="chiara_home_banner1_item2_link">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner1_item3_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner1_accordion" href="#chiara_home_banner1_item3_collapse" aria-expanded="false" aria-controls="chiara_home_banner1_item3_collapse">
                      Banner 3
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner1_item3_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner1_item3_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner1_item3_img_bg">Background Image URL:</label>
                      <input ng-model="item3_img_bg" type="text" class="form-control" id="chiara_home_banner1_item3_img_bg" ng-init="item3_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2.jpg?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item3_img_fg">Front Image URL:</label>
                      <input ng-model="item3_img_fg" type="text" class="form-control" id="chiara_home_banner1_item3_img_fg" ng-init="item3_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2a.png?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item3_alt">Image Alt:</label>
                      <input ng-model="item3_alt" type="text" class="form-control" id="chiara_home_banner1_item3_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item3_link">Link URL:</label>
                      <input ng-model="item3_link" type="text" class="form-control" id="chiara_home_banner1_item3_link">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner1_item4_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner1_accordion" href="#chiara_home_banner1_item4_collapse" aria-expanded="false" aria-controls="chiara_home_banner1_item4_collapse">
                      Banner 4
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner1_item4_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner1_item4_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner1_item4_img_bg">Background Image URL:</label>
                      <input ng-model="item4_img_bg" type="text" class="form-control" id="chiara_home_banner1_item4_img_bg" ng-init="item4_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2.jpg?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item4_img_fg">Front Image URL:</label>
                      <input ng-model="item4_img_fg" type="text" class="form-control" id="chiara_home_banner1_item4_img_fg" ng-init="item4_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2a.png?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item4_alt">Image Alt:</label>
                      <input ng-model="item4_alt" type="text" class="form-control" id="chiara_home_banner1_item4_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item4_link">Link URL:</label>
                      <input ng-model="item4_link" type="text" class="form-control" id="chiara_home_banner1_item4_link">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner1_item5_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner1_accordion" href="#chiara_home_banner1_item5_collapse" aria-expanded="false" aria-controls="chiara_home_banner1_item5_collapse">
                      Banner 5
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner1_item5_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner1_item5_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner1_item5_img_bg">Background Image URL:</label>
                      <input ng-model="item5_img_bg" type="text" class="form-control" id="chiara_home_banner1_item5_img_bg" ng-init="item5_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2.jpg?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item5_img_fg">Front Image URL:</label>
                      <input ng-model="item5_img_fg" type="text" class="form-control" id="chiara_home_banner1_item5_img_fg" ng-init="item5_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner2a.png?t=1534872900'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item5_alt">Image Alt:</label>
                      <input ng-model="item5_alt" type="text" class="form-control" id="chiara_home_banner1_item5_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner1_item5_link">Link URL:</label>
                      <input ng-model="item5_link" type="text" class="form-control" id="chiara_home_banner1_item5_link">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_home_banner1.txt'" compile="true" id="chiara_home_banner1_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_home_banner1_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_home_banner1_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_home_banner2_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_home_banner2_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_home_banner2_modal_label">Code Generator: Homepage Fullwidth Banner</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_home_banner2_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner2_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_home_banner2_accordion" href="#chiara_home_banner2_item1_collapse" aria-expanded="true" aria-controls="chiara_home_banner2_item1_collapse">
                      Banner
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner2_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_home_banner2_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner2_item1_img_bg">Background Image URL:</label>
                      <input ng-model="item1_img_bg" type="text" class="form-control" id="chiara_home_banner2_item1_img_bg" ng-init="item1_img_bg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner6.jpg?t=1534874551'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner2_item1_img_fg">Front Image URL:</label>
                      <input ng-model="item1_img_fg" type="text" class="form-control" id="chiara_home_banner2_item1_img_fg" ng-init="item1_img_fg='https://cdn7.bigcommerce.com/s-g0pakqdzwl/product_images/uploaded_images/furniture-banner6a.png?t=1534874552'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner2_item1_alt">Image Alt:</label>
                      <input ng-model="item1_alt" type="text" class="form-control" id="chiara_home_banner2_item1_alt">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner2_item1_link">Link URL:</label>
                      <input ng-model="item1_link" type="text" class="form-control" id="chiara_home_banner2_item1_link">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_home_banner2.txt'" compile="true" id="chiara_home_banner2_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_home_banner2_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_home_banner2_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_home_banner3_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_home_banner3_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_home_banner3_modal_label">Code Generator: Images Carousel</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_home_banner3_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item1_collapse" aria-expanded="true" aria-controls="chiara_home_banner3_item1_collapse">
                      Image 1
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_home_banner3_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item1_img">Background Image URL:</label>
                      <input ng-model="item1_img" type="text" class="form-control" id="chiara_home_banner3_item1_img" ng-init="item1_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand1.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item1_alt">Image Alt:</label>
                      <input ng-model="item1_alt" type="text" class="form-control" id="chiara_home_banner3_item1_alt"
                      ng-init="item1_alt='Banner1'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item1_link">Link URL:</label>
                      <input ng-model="item1_link" type="text" class="form-control" id="chiara_home_banner3_item1_link"
                      ng-init="item1_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item2_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item2_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item2_collapse">
                      Image 2
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item2_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item2_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item2_img">Background Image URL:</label>
                      <input ng-model="item2_img" type="text" class="form-control" id="chiara_home_banner3_item2_img" ng-init="item2_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand2.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item2_alt">Image Alt:</label>
                      <input ng-model="item2_alt" type="text" class="form-control" id="chiara_home_banner3_item2_alt"
                      ng-init="item2_alt='Banner2'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item2_link">Link URL:</label>
                      <input ng-model="item2_link" type="text" class="form-control" id="chiara_home_banner3_item2_link"
                      ng-init="item2_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item3_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item3_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item3_collapse">
                      Image 3
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item3_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item3_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item3_img">Background Image URL:</label>
                      <input ng-model="item3_img" type="text" class="form-control" id="chiara_home_banner3_item3_img" ng-init="item3_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand3.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item3_alt">Image Alt:</label>
                      <input ng-model="item3_alt" type="text" class="form-control" id="chiara_home_banner3_item3_alt"
                      ng-init="item3_alt='Banner3'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item3_link">Link URL:</label>
                      <input ng-model="item3_link" type="text" class="form-control" id="chiara_home_banner3_item3_link"
                      ng-init="item3_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item4_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item4_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item4_collapse">
                      Image 4
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item4_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item4_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item4_img">Background Image URL:</label>
                      <input ng-model="item4_img" type="text" class="form-control" id="chiara_home_banner3_item4_img" ng-init="item4_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand4.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item4_alt">Image Alt:</label>
                      <input ng-model="item4_alt" type="text" class="form-control" id="chiara_home_banner3_item4_alt"
                      ng-init="item4_alt='Banner4'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item4_link">Link URL:</label>
                      <input ng-model="item4_link" type="text" class="form-control" id="chiara_home_banner3_item4_link"
                      ng-init="item4_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item5_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item5_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item5_collapse">
                      Image 5
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item5_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item5_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item5_img">Background Image URL:</label>
                      <input ng-model="item5_img" type="text" class="form-control" id="chiara_home_banner3_item5_img" ng-init="item5_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand5.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item5_alt">Image Alt:</label>
                      <input ng-model="item5_alt" type="text" class="form-control" id="chiara_home_banner3_item5_alt"
                      ng-init="item5_alt='Banner5'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item5_link">Link URL:</label>
                      <input ng-model="item5_link" type="text" class="form-control" id="chiara_home_banner3_item5_link"
                      ng-init="item5_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item6_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item6_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item6_collapse">
                      Image 6
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item6_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item6_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item6_img">Background Image URL:</label>
                      <input ng-model="item6_img" type="text" class="form-control" id="chiara_home_banner3_item6_img" ng-init="item6_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand6.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item6_alt">Image Alt:</label>
                      <input ng-model="item6_alt" type="text" class="form-control" id="chiara_home_banner3_item6_alt"
                      ng-init="item6_alt='Banner6'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item6_link">Link URL:</label>
                      <input ng-model="item6_link" type="text" class="form-control" id="chiara_home_banner3_item6_link"
                      ng-init="item6_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item7_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item7_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item7_collapse">
                      Image 7
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item7_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item7_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item7_img">Background Image URL:</label>
                      <input ng-model="item7_img" type="text" class="form-control" id="chiara_home_banner3_item7_img" ng-init="item7_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand7.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item7_alt">Image Alt:</label>
                      <input ng-model="item7_alt" type="text" class="form-control" id="chiara_home_banner3_item7_alt"
                      ng-init="item7_alt='Banner7'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item7_link">Link URL:</label>
                      <input ng-model="item7_link" type="text" class="form-control" id="chiara_home_banner3_item7_link"
                      ng-init="item7_link='#'">
                    </div>
                  </div>
                </div>
              </div>
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_home_banner3_item8_heading">
                  <h4 class="panel-title">
                    <a class="collapsed" role="button" data-toggle="collapse" data-parent="#chiara_home_banner3_accordion" href="#chiara_home_banner3_item8_collapse" aria-expanded="false" aria-controls="chiara_home_banner3_item8_collapse">
                      Image 8
                    </a>
                  </h4>
                </div>
                <div id="chiara_home_banner3_item8_collapse" class="panel-collapse collapse" role="tabpanel" aria-labelledby="chiara_home_banner3_item8_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_home_banner3_item8_img">Background Image URL:</label>
                      <input ng-model="item8_img" type="text" class="form-control" id="chiara_home_banner3_item8_img" ng-init="item8_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand8.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item8_alt">Image Alt:</label>
                      <input ng-model="item8_alt" type="text" class="form-control" id="chiara_home_banner3_item8_alt"
                      ng-init="item8_alt='Banner8'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_home_banner3_item8_link">Link URL:</label>
                      <input ng-model="item8_link" type="text" class="form-control" id="chiara_home_banner3_item8_link"
                      ng-init="item8_link='#'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_home_banner3.txt'" compile="true" id="chiara_home_banner3_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_home_banner3_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_home_banner3_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_sidebar_category_banner1_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_sidebar_category_banner1_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_sidebar_category_banner1_modal_label">Code Generator: Sidebar Category Banner 1</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_sidebar_category_banner1_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_sidebar_category_banner1_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_sidebar_category_banner1_accordion" href="#chiara_sidebar_category_banner1_item1_collapse" aria-expanded="true" aria-controls="chiara_sidebar_category_banner1_item1_collapse">
                      Image
                    </a>
                  </h4>
                </div>
                <div id="chiara_sidebar_category_banner1_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_sidebar_category_banner1_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_img">Image URL:</label>
                      <input ng-model="item1_img" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_img" ng-init="item1_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_alt">Image Alt:</label>
                      <input ng-model="item1_alt" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_alt"
                      ng-init="item1_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_link">Title:</label>
                      <input ng-model="item1_title" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_title"
                      ng-init="item1_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_link">Subtitle:</label>
                      <input ng-model="item1_subtitle" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_subtitle"
                      ng-init="item1_subtitle='from &pound;29.99'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_link">Link URL:</label>
                      <input ng-model="item1_action_link" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_link"
                      ng-init="item1_action_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_link">Link Text:</label>
                      <input ng-model="item1_action_text" type="text" class="form-control" id="chiara_sidebar_category_banner1_item1_link"
                      ng-init="item1_action_text='shop now'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_sidebar_category_banner1.txt'" compile="true" id="chiara_sidebar_category_banner1_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_sidebar_category_banner1_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_sidebar_category_banner1_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_sidebar_category_banner2_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_sidebar_category_banner2_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_sidebar_category_banner2_modal_label">Code Generator: Sidebar Category Banner 2</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_sidebar_category_banner2_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_sidebar_category_banner2_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_sidebar_category_banner2_accordion" href="#chiara_sidebar_category_banner2_item1_collapse" aria-expanded="true" aria-controls="chiara_sidebar_category_banner2_item1_collapse">
                      Image
                    </a>
                  </h4>
                </div>
                <div id="chiara_sidebar_category_banner2_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_sidebar_category_banner2_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item2_img">Image URL:</label>
                      <input ng-model="item2_img" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_img" ng-init="item2_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner2_item2_alt">Image Alt:</label>
                      <input ng-model="item2_alt" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_alt"
                      ng-init="item2_alt='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner2_item2_link">Title:</label>
                      <input ng-model="item2_title" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_title"
                      ng-init="item2_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner1_item1_link">Subtitle:</label>
                      <input ng-model="item2_subtitle" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_subtitle"
                      ng-init="item2_subtitle='from &pound;29.99'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner2_item2_link">Link URL:</label>
                      <input ng-model="item2_action_link" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_link"
                      ng-init="item2_action_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_category_banner2_item2_link">Link Text:</label>
                      <input ng-model="item2_action_text" type="text" class="form-control" id="chiara_sidebar_category_banner2_item2_link"
                      ng-init="item2_action_text='shop now'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_sidebar_category_banner2.txt'" compile="true" id="chiara_sidebar_category_banner2_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_sidebar_category_banner2_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_sidebar_category_banner2_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_sidebar_brand_banner1_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_sidebar_brand_banner1_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_sidebar_brand_banner1_modal_label">Code Generator: Sidebar Brand Banner 1</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_sidebar_brand_banner1_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_sidebar_brand_banner1_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_sidebar_brand_banner1_accordion" href="#chiara_sidebar_brand_banner1_item1_collapse" aria-expanded="true" aria-controls="chiara_sidebar_brand_banner1_item1_collapse">
                      Image
                    </a>
                  </h4>
                </div>
                <div id="chiara_sidebar_brand_banner1_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_sidebar_brand_banner1_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_img">Image URL:</label>
                      <input ng-model="item1_img" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_img" ng-init="item1_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_alt">Image Alt:</label>
                      <input ng-model="item1_alt" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_alt"
                      ng-init="item1_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_link">Title:</label>
                      <input ng-model="item1_title" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_title"
                      ng-init="item1_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_link">Subtitle:</label>
                      <input ng-model="item1_subtitle" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_subtitle"
                      ng-init="item1_subtitle='from &pound;29.99'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_link">Link URL:</label>
                      <input ng-model="item1_action_link" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_link"
                      ng-init="item1_action_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_link">Link Text:</label>
                      <input ng-model="item1_action_text" type="text" class="form-control" id="chiara_sidebar_brand_banner1_item1_link"
                      ng-init="item1_action_text='shop now'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_sidebar_brand_banner1.txt'" compile="true" id="chiara_sidebar_brand_banner1_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_sidebar_brand_banner1_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_sidebar_brand_banner1_modal -->
  <!-- Modal -->
  <div class="modal fade" id="chiara_sidebar_brand_banner2_modal" tabindex="-1" role="dialog" aria-labelledby="chiara_sidebar_brand_banner2_modal_label">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
          <h4 class="modal-title" id="chiara_sidebar_brand_banner2_modal_label">Code Generator: Sidebar Brand Banner 2</h4>
        </div>
        <div class="modal-body">
          <form>
            <div class="panel-group" id="chiara_sidebar_brand_banner2_accordion" role="tablist" aria-multiselectable="true">
              <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="chiara_sidebar_brand_banner2_item1_heading">
                  <h4 class="panel-title">
                    <a role="button" data-toggle="collapse" data-parent="#chiara_sidebar_brand_banner2_accordion" href="#chiara_sidebar_brand_banner2_item1_collapse" aria-expanded="true" aria-controls="chiara_sidebar_brand_banner2_item1_collapse">
                      Image
                    </a>
                  </h4>
                </div>
                <div id="chiara_sidebar_brand_banner2_item1_collapse" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="chiara_sidebar_brand_banner2_item1_heading">
                  <div class="panel-body">
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item2_img">Image URL:</label>
                      <input ng-model="item2_img" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_img" ng-init="item2_img='https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/banner-sidebar.jpg'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner2_item2_alt">Image Alt:</label>
                      <input ng-model="item2_alt" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_alt"
                      ng-init="item2_alt='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner2_item2_link">Title:</label>
                      <input ng-model="item2_title" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_title"
                      ng-init="item2_title='beauty'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner1_item1_link">Subtitle:</label>
                      <input ng-model="item2_subtitle" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_subtitle"
                      ng-init="item2_subtitle='from &pound;29.99'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner2_item2_link">Link URL:</label>
                      <input ng-model="item2_action_link" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_link"
                      ng-init="item2_action_link='#'">
                    </div>
                    <div class="form-group">
                      <label for="chiara_sidebar_brand_banner2_item2_link">Link Text:</label>
                      <input ng-model="item2_action_text" type="text" class="form-control" id="chiara_sidebar_brand_banner2_item2_link"
                      ng-init="item2_action_text='shop now'">
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div hljs include="'/samples/chiara_sidebar_brand_banner2.txt'" compile="true" id="chiara_sidebar_brand_banner2_code" class="highlight-code"></div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary" data-clipboard-target="#chiara_sidebar_brand_banner2_code">Copy Code</button>
        </div>
      </div>
    </div>
  </div><!-- modal #chiara_sidebar_brand_banner2_modal -->
</div>


# Wine CUSTOMIZATION

## HEADERS

## --- Order Online Button

![header](img/homepage-header-section-1.png)

---

* **HTML Content:**

```html
{{#partial 'feellio-cuisine-navpages-extra-links'}}
  <li class="navPages-item">
      <a class="navPages-action navPages-action--button-primary" href="/contact-us/">Order Online</a>
  </li>
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![footer](img/how-to-overwrite-a-section-content.png)

---

## FOOTERS

![Footer](img/footer-style-1.png)

--- 

## --- Configures

Configure the footer in **Theme Editor** > **Footer** section. 

* **You can choose footer style.**
* **Change text colors, background color of footer.**
* **Show web page links, categories, brands and custom links.**
* **Newsletter form support top or right position of the footer.**
* **Change text colors, background color of the copyright section.**
* **Show/hide/edit copyright links.**
* **Show/hide payment icons.**

![Footer](img/footer-configutation.png)

--- 

## --- Section Footer Info

![footer](img/homepage-footer-info.png)

---

* **HTML Content:**

```html
{{#partial "chiara-footer-info"}}
<section class="footer-info">
    <div class="footer-info-left">
        <article class="footer-info-col" data-section-type="footer-webPages">
            <p>Sed ac mauris sit amet ante. Maecenas eu nibh. Aliquam fermentum eget, suscipit congue id, lacinia accumsan lectus nec lectus lectus, luctus et ultrices metus imperdiet facilisis est eu quam. Phasellus ut ante. Donec mi. Suspendisse adipiscing.</p>
            <p><a href="#">Read more ...</a></p>
            <p class="footer-info-contact"><strong>Contact us:</strong> <a href="tel:111-111-1111">111-111-1111</a><br>
                <strong>Write us:</strong> <a href="mailto:contact@example.com">contact@example.com</a></p>
        </article>
        <article class="footer-info-col" data-section-type="footer-webPages">
            <ul class="footer-info-list is-open">
                <li><a href="#">Aenean sollicitudin</a></li>
                <li><a href="#">Duis sed odio sit amet</a></li>
                <li><a href="#">Morbi accumsan</a></li>
                <li><a href="#">Nam nec tellus</a></li>
                <li><a href="#">Class aptent taciti</a></li>
                <li><a href="#">Phasellus vel ligula</a></li>
            </ul>
        </article>
    </div>
    <div class="footer-info-right">
        {{#if settings.show_newsletter_box}}
        {{#if theme_settings.footer_newsletter_position '===' 'right'}}
            {{> components/chiara/common/footer-newsletter}}
        {{/if}}
        {{/if}}
        {{#if theme_settings.social_icon_placement_bottom '!==' 'bottom_none'}}
        <article class="footer-info-col footer-info-col--socials" data-section-type="newsletterSubscription">
            <h5 class="footer-info-heading">{{lang 'social.connect'}}</h5>
            {{> components/common/social-links}}

            {{#if theme_settings.payment_icons_position '===' 'footer_right'}}
                <h5 class="footer-info-heading">{{lang 'footer.accept_payments'}}</h5>
                {{> components/common/payment-icons}}

                {{#if theme_settings.geotrust_ssl_common_name}}
                    <div class="footer-geotrust-ssl-seal">
                        {{> components/common/geotrust-ssl-seal}}
                    </div>
                {{/if}}
            {{/if}}
        </article>
        {{/if}}
    </div>
</section>
<section class="footer-info footer-info--alt">
    <article class="footer-info-col">
        <ul class="footer-info-list is-open">
            <li><a href="#">Store Location</a></li>
            <li><a href="#">Party Booking</a></li>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">Careers</a></li>
            <li><a href="#">Feedback</a></li>
            <li><a href="#">Privacy Policy</a></li>
            <li><a href="#">Quality Policy</a></li>
            <li><a href="#">Terms & Conditions</a></li>
        </ul>
    </article>
</section>
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![footer](img/how-to-overwrite-a-section-content.png)

---

## HOMEPAGE SECTIONS:

## --- Sections Manager

You can select the sections displayed on the homepage (maximum 10 sections) in **Theme Editor** > **Homepage** > **Sections**.

![Homepage Sections Manager](img/homepage-sections-manager.png)

--- 

### List of available sections name: ###

* **feellio-cuisine-features**
* **feellio-cuisine-menu**
* **feellio-cuisine-blog**
* **feellio-cuisine-banners**
* **feellio-cuisine-offers**
* **feellio-cuisine-contact**
* **feellio-cuisine-reservation**
* **feellio-cuisine-instagram**
* **feellio-cuisine-gmap**

* **new-products**
* **top-products**
* **featured-products**

###Default feellio theme sections: ###

* **feellio-cuisine-features**
* **feellio-cuisine-menu**
* **feellio-cuisine-blog**
* **feellio-cuisine-banners**
* **feellio-cuisine-offers**
* **feellio-cuisine-contact**
* **feellio-cuisine-reservation**
* **feellio-cuisine-instagram**
* **feellio-cuisine-gmap**



## --- Products Sections (New / Featured / Bestselling)

**By default, these sections will not appear on the homepage. However, you can use it.**

---

![Homepage products section](img/homepage-products-section.png)

---

Configure New Products, Featured Products, Bestselling Products showing on the home page in **Theme Editor** > **Homepage**:

* **Number of products to display.**
* **Heading of the new, featured, bestselling product blocks.**
* **Sub-heading.**
* **Columns (number of products per row).**
* **Columns on tablet.**
* **Columns on mobile.**
* **Type (Grid or List).**
* **Style (default or parallax).**

![Homepage products section 2](img/homepage-products-section-2.png)

---

## --- Section Cuisine Features

![homepage-section](img/homepage-style-1-section-1.png)

---

* **HTML Content:**

```html
{{#partial "feellio-cuisine-features"}}
<div class="chiara-section feellio-section--cuisineFeatures">
    <div class="feellioCuisineFeatures">

        <div class="feellioCuisine-section-heading wow fadeIn">
            <h3 class="feellioCuisine-section-heading-main page-heading">A Smart Combination</h3>
            <p class="feellioCuisine-section-heading-sub">Tranditional taste</p>
        </div>

        <div class="feellioCuisineFeatures-chefRow">
            <div class="feellioCuisineFeatures-chefImg wow fadeIn">
                <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="//cdn11.bigcommerce.com/s-a91prfobiq/product_images/uploaded_images/feellio-cuisine-features-chef.jpg?t=1542958697" width="426" height="620" alt="426x620">
            </div>

            <ul class="feellioCuisineFeatures-list feellioCuisineFeatures-list--left">
                <li class="feellioCuisineFeatures-item wow fadeIn">
                    <div class="feellioCuisineFeatures-icon"><svg><use xlink:href="#icon-feellio-100percent" /></svg></div>
                    <div class="feellioCuisineFeatures-item-title">100% Hygiene</div>
                    <div class="feellioCuisineFeatures-item-desc">Cleanliness is No. 1 priority for us.</div>
                </li>
                <li class="feellioCuisineFeatures-item wow fadeIn">
                    <div class="feellioCuisineFeatures-icon"><svg><use xlink:href="#icon-feellio-dinner" /></svg></div>
                    <div class="feellioCuisineFeatures-item-title">Dine in</div>
                    <div class="feellioCuisineFeatures-item-desc">State of the art dining experience.</div>
                </li>
                <li class="feellioCuisineFeatures-item wow fadeIn">
                    <div class="feellioCuisineFeatures-icon"><svg><use xlink:href="#icon-feellio-party" /></svg></div>
                    <div class="feellioCuisineFeatures-item-title">Party hosting</div>
                    <div class="feellioCuisineFeatures-item-desc">Plan a event with us.</div>
                </li>
            </ul>

            <ul class="feellioCuisineFeatures-list feellioCuisineFeatures-list--right">
                <li class="feellioCuisineFeatures-item wow fadeIn">
                    <div class="feellioCuisineFeatures-icon"><svg><use xlink:href="#icon-feellio-food" /></svg></div>
                    <div class="feellioCuisineFeatures-item-title">Traditional taste</div>
                    <div class="feellioCuisineFeatures-item-desc">Chowking guarantees authentic taste.</div>
                </li>
                <li class="feellioCuisineFeatures-item wow fadeIn">
                    <div class="feellioCuisineFeatures-icon"><svg><use xlink:href="#icon-feellio-takeaway" /></svg></div>
                    <div class="feellioCuisineFeatures-item-title">Take away</div>
                    <div class="feellioCuisineFeatures-item-desc">Fresh & convinient packing</div>
                </li>
                <li class="feellioCuisineFeatures-item wow fadeIn">
                    <div class="feellioCuisineFeatures-icon"><svg><use xlink:href="#icon-feellio-store" /></svg></div>
                    <div class="feellioCuisineFeatures-item-title">30+ stores</div>
                    <div class="feellioCuisineFeatures-item-desc">We're always close to you</div>
                </li>
            </ul>
        </div>

        <div class="feellioCuisineFeatures-parallax wow fadeIn">
            <div class="feellioCuisineFeatures-parallax-img"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="//cdn11.bigcommerce.com/s-a91prfobiq/product_images/uploaded_images/feellio-cuisine-features-parallax-bg.jpg?t=1542958590" width="1920" height="679" alt="1920x679"></div>
            <h4 class="feellioCuisineFeatures-parallax-title">Host your party!</h4>
            <div class="feellioCuisineFeatures-parallax-desc">Make it memorable</div>
            <div class="feellioCuisineFeatures-parallax-button"><a class="button button--primary" href="#">Get a perfect location</a></div>
        </div>

    </div>
</div>
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Cuisine Menu

![homepage-section](img/homepage-style-1-section-2.png)

---

* **HTML Content:**

```html
{{#partial "feellio-cuisine-menu"}}
<div class="chiara-section feellio-section--cuisineMenu">
    <div class="feellioCuisineMenu wow fadeIn">

        <div class="feellioCuisine-section-heading wow fadeIn">
            <h3 class="feellioCuisine-section-heading-main page-heading">Delivering top quality food products</h3>
            <p class="feellioCuisine-section-heading-sub">Menu</p>
        </div>

        <ul class="feellioCuisineMenu-list wow fadeIn">
            <li class="feellioCuisineMenu-item"><a href="#">All</a></li>
            <li class="feellioCuisineMenu-item"><a href="#">Breakfast</a></li>
            <li class="feellioCuisineMenu-item"><a href="#">Lunch</a></li>
            <li class="feellioCuisineMenu-item"><a href="#">Dinner</a></li>
            <li class="feellioCuisineMenu-item"><a href="#">Drink</a></li>
            <li class="feellioCuisineMenu-item"><a href="#">Desserts</a></li>
            <li class="feellioCuisineMenu-item"><a href="#">Party</a></li>
        </ul>

    </div>
</div>
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Cuisine Blog

![homepage-section](img/homepage-style-1-section-3.png)

---

**This section automatically displays the newest blog posts. If you want to customize this block, you can copy the HTML below into `templates/coupon-custom.html` and freely edit it.**

* **HTML Content:**

```html
{{#partial "feellio-cuisine-blog"}}
<div class="chiara-section feellio-section--cusineBlog">
    <div class="feellioCuisineBlog">
        <div class="feellioCuisineBlog-blog">
            <ul class="feellioCuisineBlog-posts" data-slick='{
                "dots": false,
                "arrows": true,
                "prevArrow": "&lt;a class=slick-prev&gt;&lt;svg&gt;&lt;use xlink:href=#icon-feellio-slider-arrow-left /&gt;&lt;/svg&gt;&lt;/a&gt;",
                "nextArrow": "&lt;a class=slick-next&gt;&lt;svg&gt;&lt;use xlink:href=#icon-feellio-slider-arrow-right /&gt;&lt;/svg&gt;&lt;/a&gt;",
                "infinite": true,
                "mobileFirst": true,
                "slidesToShow": 1,
                "slidesToScroll": 1,
                "autoplay": true,
                "autoplaySpeed": 5000,
                "lazyLoad": "anticipated"
            }'>
                {{#each blog.recent_posts}}
                    <li class="feellioCuisineBlog-posts-item">
                        <div class="feellioCuisineBlog-post-date" data-moment-input-format="MMM Do YYYY">{{date_published}}</div>
                        <h4 class="feellioCuisineBlog-post-title"><a href="{{url}}">{{title}}</a></h4>
                        <div class="feellioCuisineBlog-post-summary">{{{summary}}}</div>
                    </li>
                {{/each}}
            </ul>
        </div>
    </div>
</div>
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Cuisine Banners

![homepage-section](img/homepage-style-1-section-4.png)

---

* **HTML Content:**

```html
{{#partial "feellio-cuisine-banners"}}
<div class="chiara-section feellio-section--cuisineBanners">
    <div class="feellioCuisineBanners">

        <div class="feellioCuisineBanners-banner">
            <div class="feellioCuisineBanners-img wow fadeIn"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="//cdn11.bigcommerce.com/s-a91prfobiq/product_images/uploaded_images/feellio-cuisine-banners1.jpg?t=1543209083" width="588" height="576" alt="576" /></a></div>
            <div class="feellioCuisineBanners-body wow fadeIn" data-wow-delay="200ms">
                <h3 class="feellioCuisineBanners-title">Malay Mixed Rice</h3>
                <div class="feellioCuisineBanners-content">We create, make and serve fresh food to go. We love to share good food with you and your friends. The vast majority of our shops work with local charity ...</div>
                <div class="feellioCuisineBanners-price">$90</div>
            </div>
        </div>

        <div class="feellioCuisineBanners-banner">
            <div class="feellioCuisineBanners-img wow fadeIn"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="//cdn11.bigcommerce.com/s-a91prfobiq/product_images/uploaded_images/feellio-cuisine-banners2.jpg?t=1543209084" width="556" height="622" alt="556x622" /></a></div>
            <div class="feellioCuisineBanners-body wow fadeIn" data-wow-delay="200ms">
                <h3 class="feellioCuisineBanners-title feellioCuisineBanners-title--alt">Appetizer</h3>
                <div class="feellioCuisineBanners-content feellioCuisineBanners-content--alt">Give you the <strong>delicious</strong> to heat up your family</div>
                <div class="feellioCuisineBanners-price">$55</div>
            </div>
        </div>

        <div class="feellioCuisineBanners-banner">
            <div class="feellioCuisineBanners-img wow fadeIn"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="//cdn11.bigcommerce.com/s-a91prfobiq/product_images/uploaded_images/feellio-cuisine-banners3.jpg?t=1543209086" width="596" height="659" alt="659" /></a></div>
            <div class="feellioCuisineBanners-body wow fadeIn" data-wow-delay="200ms">
                <h3 class="feellioCuisineBanners-title feellioCuisineBanners-title--alt feellioCuisineBanners-title--xl">150+</h3>
                <div class="feellioCuisineBanners-content feellioCuisineBanners-content--alt">Let's <strong>come & experience</strong> our delicious and collection</div>
                <div class="feellioCuisineBanners-price">$65</div>
            </div>
        </div>

        <div class="feellioCuisineBanners-buttonRow wow fadeIn">
            <a class="button button--primary" href="#">Our Menu List</a>
        </div>
    </div>
</div>
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Cuisine Offers

![homepage-section](img/homepage-style-1-section-5.png)

---

* **HTML Content:**

```html
{{#partial "feellio-cuisine-offers"}}
<div class="chiara-section feellio-section--cuisineOffers">
    <div class="feellioCuisineOffers">
        <div class="feellioCuisineOffers-bg wow fadeIn">
            <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="//cdn11.bigcommerce.com/s-a91prfobiq/product_images/uploaded_images/feellio-cuisine-offers-bg.jpg?t=1543222873" width="1920" height="1304" alt="1920x1304" />
        </div>

        <div class="feellioCuisine-section-heading wow fadeIn">
            <h3 class="feellioCuisine-section-heading-main page-heading">Claim the taste!</h3>
            <p class="feellioCuisine-section-heading-sub">Offers &amp; Promotions</p>
        </div>
        
        <ul class="feellioCuisineOffers-grid">
            <li class="feellioCuisineOffers-item feellioCuisineOffers-item--1 wow fadeIn">
                <div class="feellioCuisineOffers-item-img feellioCuisineOffers-item-img--right">
                    <a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="//cdn11.bigcommerce.com/s-a91prfobiq/product_images/uploaded_images/feellio-cuisine-offers1.jpg?t=1543222874" width="390" height="390" alt="390x390" /></a>
                </div>
            </li>
            <li class="feellioCuisineOffers-item feellioCuisineOffers-item--2 wow fadeIn" data-wow-delay="200ms">
                <div class="feellioCuisineOffers-item-body">
                    <h4 class="feellioCuisineOffers-item-title">10% off on<br/>shrimp delicacy</h4>
                    <div class="feellioCuisineOffers-item-content">Most food has its origin in plants. Some food is obtained directly from plants; but even animals that are used as food </div>
                    <div class="feellioCuisineOffers-item-action"><a href="#">Claim Now <svg class="icon"><use xlink:href="#icon-feellio-slider-arrow-right" /></svg></a></div>
                </div>
            </li>
            <li class="feellioCuisineOffers-item feellioCuisineOffers-item--3 wow fadeIn" data-wow-delay="400ms">
                <div class="feellioCuisineOffers-item-img">
                    <a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="//cdn11.bigcommerce.com/s-a91prfobiq/product_images/uploaded_images/feellio-cuisine-offers2.jpg?t=1543222875" width="390" height="390" alt="390x390" /></a>
                </div>
            </li>
            <li class="feellioCuisineOffers-item feellioCuisineOffers-item--6 wow fadeIn" data-wow-delay="400ms">
                <div class="feellioCuisineOffers-item-body">
                    <h4 class="feellioCuisineOffers-item-title">Egg schezvan<br/>noodles at $18.99</h4>
                    <div class="feellioCuisineOffers-item-content">Many scholars claim that the rhetorical function of food is to represent the culture of a country, and that it can be used as a form of communication.</div>
                    <div class="feellioCuisineOffers-item-action"><a href="#">Claim Now <svg class="icon"><use xlink:href="#icon-feellio-slider-arrow-right" /></svg></a></div>
                </div>
            </li>
            <li class="feellioCuisineOffers-item feellioCuisineOffers-item--5 wow fadeIn" data-wow-delay="200ms">
                <div class="feellioCuisineOffers-item-img feellioCuisineOffers-item-img--left">
                    <a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="//cdn11.bigcommerce.com/s-a91prfobiq/product_images/uploaded_images/feellio-cuisine-offers3.jpg?t=1543222877" width="390" height="390" alt="390x390" /></a>
                </div>
            </li>
            <li class="feellioCuisineOffers-item feellioCuisineOffers-item--4 wow fadeIn">
                <div class="feellioCuisineOffers-item-body">
                    <h4 class="feellioCuisineOffers-item-title">Mixed meals<br/>at $ 25.99</h4>
                    <div class="feellioCuisineOffers-item-content">Many plants and plant parts are eaten as food and around 2,000 plant species are cultivated for food.</div>
                    <div class="feellioCuisineOffers-item-action"><a href="#">Claim Now <svg class="icon"><use xlink:href="#icon-feellio-slider-arrow-right" /></svg></a></div>
                </div>
            </li>
        </ul>

        <div class="feellioCuisineOffers-buttonRow wow fadeIn">
            <a class="button button--primary" href="#">View All Offers</a>
        </div>
    </div>
</div>
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Cuisine Contact

![homepage-section](img/homepage-style-1-section-6.png)

---

* **HTML Content:**

```html
{{#partial "feellio-cuisine-contact"}}
<div class="chiara-section feellio-section--cuisineContact">
    <div class="feellioCuisineContact">

        <div class="feellioCuisine-section-heading wow fadeIn">
            <h3 class="feellioCuisine-section-heading-main page-heading">Order Your Diet!</h3>
            <p class="feellioCuisine-section-heading-sub">Say Hello!</p>
        </div>

        <div class="feellioCuisineContact-info">
            <div class="feellioCuisineContact-info-left wow fadeIn">
                <h4 class="feellioCuisineContact-info-title">Head Quarters</h4>
                <div class="feellioCuisineContact-info-content">
                    <p><strong>Mon - Sun:</strong><br>10:00 am - 9:30 pm</p>
                    <p><strong>Restaurant:</strong><br>123 Street, Chicago<br>Geogria, USA</p>
                </div>
            </div>
            <div class="feellioCuisineContact-info-right wow fadeIn" data-wow-delay="200ms">
                <h4 class="feellioCuisineContact-info-title">Contact</h4>
                <div class="feellioCuisineContact-info-content">
                    <p><strong>Email:</strong><br>contact@example.com</p>
                    <p><strong>Tel: 111-111-1111<br>Fax: 222-222-2222</strong></p>
                </div>
            </div>
        </div>

    </div>
</div>
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Cuisine Reservation

**Note: There must be a contact page with link `/contact-us/` in order to display this contact form. If you don't have a contact us page, or your contact us page's link is different, please create another contact us page with the same link `/contact-us/` exactly.**

![homepage-section](img/homepage-style-1-section-7.png)

---

* **HTML Content:**

```html
{{#partial "feellio-cuisine-reservation"}}
<div class="chiara-section feellio-section--cuisineReservation">
    <div class="feellioCuisineReservation">

        <div class="feellioCuisineReservation-bg wow fadeIn">
            <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="//cdn11.bigcommerce.com/s-a91prfobiq/product_images/uploaded_images/feellio-cuisine-features-reservation-bg.jpg?t=1543295579" width="1920" height="1295" alt="1920x1295" />
        </div>

        <h3 class="feellioCuisineReservation-heading wow fadeIn">Reservation</h3>
        <div class="feellioCuisineReservation-desc wow fadeIn">Feel free to drag and drop me anywhere you like on your page. I’m a great place for you to tell a story and let your users know a little more about you.</div>

        {{inject 'contactEmail' (lang 'forms.validate.contact.email_address')}}
        {{inject 'contactQuestion' 'You must enter a message'}}
        <div class="feellioCuisineReservation-formContainer wow fadeIn" data-feellio-cuisine-reservation></div>

    </div>
</div>
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Cuisine Instagram

You need to set a Instagram access token key in **Theme Editor** > **Homepage**

![homepage-section](img/homepage-instagram-setting.png)

Use this tool to generate token: `http://bit.ly/2ACD7uM`

![homepage-section](img/homepage-style-1-section-8.png)

---

* **HTML Content:**

```html
{{#partial "feellio-cuisine-instagram"}}
{{#if theme_settings.instagram_token}}
<div class="chiara-section feellio-section--cuisineInstagram">
    <div class="feellioCuisineInstagram wow fadeIn">

        <div id="instafeed" class="feellioCuisineInstagram-instafeed"></div>
        <script type="text/javascript" src="{{cdn '/assets/vendor/instafeed/instafeed.min.js'}}"></script>
        <script type="text/javascript">
        // <![[
            (function() {
                "use strict";
                var feed = new Instafeed({
                    // get: 'user',
                    get: 'tagged',
                    tagName: 'feelliocuisine',
                    // userId: '{{first (split theme_settings.instagram_token ".")}}',
                    accessToken: '{{theme_settings.instagram_token}}',
                    resolution: 'standard_resolution',
                    template: '<div class="feellioCuisineInstagram-instafeed-item"><a href="{'+'{link}}" target="_blank" id="{'+'{id}}"><img src="{'+'{image}}" /></a></div>',
                    sortBy: 'most-recent',
                    limit: 4,
                    links: false
                });
                feed.run();
            })();
        // ]]>
        </script>
        
    </div>
</div>
{{/if}}
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Cuisine GMAP

![homepage-section](img/homepage-style-1-section-9.png)

---

You can change the location by change the lat and lng at line  `lat: -34.397, lng: 150.644`.

Use this tool to find lat and lng of a location: `https://www.latlong.net/`

* **HTML Content:**

```html
{{#partial "feellio-cuisine-gmap"}}
<div class="chiara-section feellio-section--cuisineGmap">
    <div class="feellioCuisineGmap wow fadeIn">
        <div id="feellioCuisineGmap-map" class="feellioCuisineGmap-map"></div>
        <script>
            function feellioCuisineGmap_initMap() {
                var loc = { lat: -34.397, lng: 150.644 };
                var map = new google.maps.Map(document.getElementById('feellioCuisineGmap-map'), {
                    center: loc,
                    zoom: 12
                });
                var marker = new google.maps.Marker({position: loc, map: map});
            }
        </script>
        <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCNJlECIvcxoAuASnEsItaKAuX1ju_eFko&callback=feellioCuisineGmap_initMap" async defer></script>
    </div>
</div>
{{/partial}}
```

---

* You can change content of this section by edit the file `templates/coupon-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Wine Banner Three

![homepage-section](img/section-wine-banner-three.png)

---

* **HTML Content:**

```html
{{#block "feellio-wine-banner"}}
<div class="chiara-section feellio-section--wineBanner">
    <div class="feellioWineBanner wow fadeIn">
        <div class="feellioWineBanner-img">
                <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/wine-banner-1.jpg" alt="wine-banner-1.jpg">
        </div>
        <div class="container">
            <div class="feellioWineBanner-nav">
                    <div class="feellioWineMenu">
                            <div class="feellioWineMenu-item">
                                <a href="#">
                                    <i class="icon">
                                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve"> <path d="M188.275,157.013V8.533c0-4.71-3.823-8.533-8.533-8.533h-51.2c-4.71,0-8.533,3.823-8.533,8.533v148.48 c-31.727,17.954-51.209,51.2-51.2,87.979v258.475c0,4.719,3.823,8.533,8.533,8.533h153.6c4.71,0,8.533-3.814,8.533-8.533V245.001 C239.483,208.213,220.002,174.967,188.275,157.013z M222.408,494.933H85.875V244.992c-0.017-32.06,17.801-60.885,46.481-75.221 c2.893-1.451,4.719-4.403,4.719-7.637V17.067h34.133v145.067c0,3.234,1.826,6.195,4.719,7.637 c28.681,14.327,46.49,43.153,46.481,75.221V494.933z"/> <rect x="128.516" y="42.667" width="51.2" height="17.067"/> <path d="M442.397,276.207l-15.275-106.752c-0.597-4.198-4.198-7.322-8.448-7.322h-102.4c-4.241,0-7.842,3.123-8.456,7.322 l-15.266,106.283c-1.451,9.728-0.922,19.482,1.502,28.817l1.485,6.255c8.277,33.041,37.854,56.115,71.919,56.124 c0.051,0,0.085,0,0.128,0c33.843,0,63.369-22.869,71.851-55.808l1.399-5.956C443.319,295.646,443.839,285.884,442.397,276.207z M424.281,301.056l-1.408,5.973c-6.502,25.233-29.227,42.837-55.287,42.837c-0.043,0-0.077,0-0.111,0 c-26.232,0-49.007-17.766-55.347-43.093l-1.502-6.332c-1.903-7.279-2.295-14.746-1.178-22.229l14.217-99.012h87.612l14.242,99.473 C426.628,286.114,426.235,293.581,424.281,301.056z"/> <rect x="358.916" y="358.4" width="17.067" height="110.933"/> <path d="M384.541,460.8h-34.133c-23.526,0-42.667,19.14-42.667,42.667c0,4.719,3.814,8.533,8.533,8.533h102.4 c4.719,0,8.533-3.814,8.533-8.533C427.208,479.94,408.068,460.8,384.541,460.8z M326.267,494.933 c3.524-9.933,13.022-17.067,24.141-17.067h34.133c11.127,0,20.617,7.134,24.141,17.067H326.267z"/> <rect x="299.182" y="281.6" width="136.533" height="17.067"/> <rect x="128.516" y="119.467" width="51.2" height="17.067"/> <path d="M196.808,264.533h-85.333c-4.71,0-8.533,3.814-8.533,8.533v153.6c0,4.719,3.823,8.533,8.533,8.533h85.333 c4.71,0,8.533-3.814,8.533-8.533v-153.6C205.341,268.348,201.518,264.533,196.808,264.533z M188.275,418.133h-68.267V281.6h68.267 V418.133z"/> </svg>
                                    </i>
                                mezcal
                                </a>
                            </div>
                            <div class="feellioWineMenu-item">
                                <a href="#">
                                    <i class="icon">
                                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 478.591 478.591" style="enable-background:new 0 0 478.591 478.591;" xml:space="preserve"> <path d="M256.095,222.631c-0.266-0.027-0.533-0.04-0.8-0.04h-90.152l-16.128-50.512c-5.129-19.418-16.004-36.835-31.2-49.968 c-12.765-11.036-21.9-25.669-26.208-41.984L72.015,5.943c-0.544-2.049-1.879-3.799-3.712-4.864 c-1.835-1.071-4.023-1.359-6.072-0.8L23.559,10.471c-4.271,1.129-6.819,5.508-5.689,9.779c0,0.002,0.001,0.003,0.001,0.005 l19.6,74.184c4.321,16.309,3.61,33.543-2.04,49.44c-6.712,18.816-7.596,39.218-2.536,58.544l4.456,20.168H15.295 c-2.305,0-4.497,0.995-6.016,2.728c-1.52,1.735-2.217,4.042-1.912,6.328l32,240c0.529,3.974,3.919,6.943,7.928,6.944h184 c4.109,0,7.549-3.112,7.96-7.2l24-240C263.697,226.995,260.491,223.073,256.095,222.631z M133.695,176.551l-0.04-0.032 l14.688,46.072H92.711l-10.952-27.384l51.648-19.36C133.479,176.087,133.591,176.311,133.695,176.551z M70.543,63.023l5.6,21.2 c5.132,19.417,16.006,36.833,31.2,49.968c8.498,7.448,15.4,16.54,20.288,26.728l-59.152,22.176 c-4.137,1.552-6.232,6.164-4.679,10.301c0.021,0.055,0.042,0.109,0.063,0.163l11.616,29.032H53.695l-5.264-23.936 c-4.309-16.317-3.59-33.555,2.064-49.456c6.711-18.926,7.548-39.438,2.4-58.848l-5.6-21.512L70.543,63.023z M35.391,23.895 l23.2-6.128l7.904,29.792l-23.288,5.816L35.391,23.895z M224.095,462.591H54.303l-29.864-224h222.056L224.095,462.591z"/> <path d="M367.295,350.591v-136c0-4.418-3.582-8-8-8h-80c-4.418,0-8,3.582-8,8v136c0.043,23.397,16.934,43.361,40,47.28v64.72h-32 c-4.418,0-8,3.582-8,8s3.582,8,8,8h80c4.418,0,8-3.582,8-8s-3.582-8-8-8h-32v-64.72 C350.361,393.952,367.251,373.988,367.295,350.591z M287.295,222.591h64v24h-64V222.591z M319.295,382.591 c-17.673,0-32-14.327-32-32v-88h64v88C351.295,368.264,336.968,382.591,319.295,382.591z"/> <path d="M471.295,350.591v-136c0-4.418-3.582-8-8-8h-80c-4.418,0-8,3.582-8,8v136c0.043,23.397,16.934,43.361,40,47.28v64.72h-32 c-4.418,0-8,3.582-8,8s3.582,8,8,8h80c4.418,0,8-3.582,8-8s-3.582-8-8-8h-32v-64.72 C454.361,393.952,471.251,373.988,471.295,350.591z M391.295,222.591h64v24h-64V222.591z M423.295,382.591 c-17.673,0-32-14.327-32-32v-88h64v88C455.295,368.264,440.968,382.591,423.295,382.591z"/> </svg>
                                    </i>
                                champagne
                                </a>
                            </div>
                            <div class="feellioWineMenu-item">
                                <a href="#">
                                    <i class="icon">
                                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 19.86 19.86" style="enable-background:new 0 0 19.86 19.86;" xml:space="preserve" > <path d="M13.299,15.84c-0.001-0.143-0.002-0.283-0.004-0.419c-0.024-1.808-0.124-2.97-0.188-3.716 c-0.001-0.014-0.002-0.028-0.004-0.041l-0.03-0.354c-0.001-0.008-0.003-0.018-0.003-0.024c-0.04-0.406-0.333-1.498-0.704-2.88 c-0.525-1.954-1.404-5.227-1.204-5.625c0.406-0.513,0.216-1.025,0.015-1.287c0.024-0.19,0.061-0.619-0.015-1 C11.071,0.045,10.02,0,10.01,0C9.98,0,9.953,0.002,9.93,0.004C9.906,0.002,9.879,0,9.85,0C9.839,0,8.789,0.045,8.699,0.494 c-0.076,0.381-0.039,0.81-0.015,1c-0.201,0.262-0.392,0.773,0.01,1.28C8.899,3.179,8.02,6.452,7.495,8.407 c-0.371,1.381-0.664,2.473-0.704,2.88c-0.001,0.007-0.003,0.018-0.003,0.023l-0.03,0.354c-0.001,0.013-0.002,0.028-0.004,0.041 c-0.065,0.746-0.164,1.905-0.189,3.716c-0.002,0.137-0.003,0.275-0.004,0.419c-0.006,0.858,0.004,1.847,0.041,2.997 c0.02,0.212,0.078,0.848,2.759,0.999c0,0,0.384,0.028,0.564,0.022c0.19,0.005,0.585-0.023,0.585-0.023 c2.671-0.152,2.729-0.787,2.75-1.011C13.295,17.68,13.306,16.695,13.299,15.84z M9.095,0.612c0.067-0.075,0.476-0.19,0.792-0.19 c0.003,0,0.007,0,0.01,0l0.08,0.003l0.033-0.006c0.271,0,0.688,0.117,0.741,0.157c0.047,0.234,0.041,0.496,0.027,0.686H9.081 C9.065,1.076,9.057,0.824,9.095,0.612z M9.027,2.521c-0.331-0.419-0.01-0.779,0.027-0.817L9.078,1.68h1.704l0.024,0.025 c0.015,0.015,0.368,0.385,0.027,0.816c-0.272,0.344-0.007,1.691,0.771,4.652h-0.236c-0.129-0.501-0.713-0.87-1.438-0.87 S8.62,6.671,8.491,7.173H8.257C9.034,4.212,9.299,2.865,9.027,2.521z M7.9,8.516c0.087-0.325,0.168-0.63,0.247-0.925h0.346 c0.129,0.502,0.713,0.87,1.438,0.87s1.309-0.369,1.438-0.87h0.346c0.077,0.296,0.158,0.6,0.245,0.925 c0.328,1.22,0.636,2.366,0.687,2.771H7.214C7.264,10.883,7.572,9.736,7.9,8.516z M12.841,18.799 c-0.017,0.191-0.573,0.538-2.55,0.629l-0.126,0.018c-0.062,0-0.143-0.002-0.239-0.004c-0.057,0.002-0.109,0.002-0.155,0.004 l-0.2-0.018c-1.976-0.091-2.533-0.438-2.549-0.615c-0.036-1.141-0.046-2.121-0.04-2.972h5.9 C12.887,16.688,12.877,17.665,12.841,18.799z"/> </svg>
                                    </i>
                                rose
                                </a>
                            </div>
                            <div class="feellioWineMenu-item">
                                <a href="#">
                                    <i class="icon">
                                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 150 150"><path d="M102,8.17H60.32a8.51,8.51,0,0,0-8.5,8.5v4a8.52,8.52,0,0,0,8.5,8.5H79.16V63h4V29.17H102a8.51,8.51,0,0,0,8.5-8.5v-4A8.51,8.51,0,0,0,102,8.17Zm5.5,12.5a5.51,5.51,0,0,1-5.5,5.5H60.32a5.51,5.51,0,0,1-5.5-5.5v-4a5.5,5.5,0,0,1,5.5-5.5H102a5.5,5.5,0,0,1,5.5,5.5Z"/><path d="M93.91,113.73v-23A5.66,5.66,0,0,0,98,85.36V79.14a5.83,5.83,0,0,0-6-5.64H71.68a5.83,5.83,0,0,0-6,5.64v6.22a5.72,5.72,0,0,0,4.49,5.46l.41.09v21.85A28.81,28.81,0,0,0,52.41,139.5c0,.2,0,.41,0,.6l.09,1.4H109.8l.09-1.4a5.93,5.93,0,0,0,0-.6A28.82,28.82,0,0,0,93.91,113.73ZM68.68,85.36V79.14a2.84,2.84,0,0,1,3-2.64H92a2.84,2.84,0,0,1,3,2.64v6.22a2.7,2.7,0,0,1-2,2.5A3.43,3.43,0,0,1,92,88H71.68a3.27,3.27,0,0,1-.78-.09A2.75,2.75,0,0,1,68.68,85.36ZM55.43,138.5a25.79,25.79,0,0,1,17.15-23.29l1-.35V91.5H90.91v24.15l.88.4a25.8,25.8,0,0,1,15.1,22.45Z"/></svg>
                                    </i>
                                accessories
                                </a>
                            </div>
                            <div class="feellioWineMenu-item">
                                <a href="#">
                                    <i class="icon">
                                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve"> <path d="M308.288,147.725c-2.859-2.375-6.038-3.566-9.544-3.566c-4.521,0-7.773,1.921-9.762,5.76l-97.641,199.936 c-0.725,1.83-1.085,3.385-1.085,4.662c0,3.107,1.243,5.896,3.736,8.365c2.49,2.468,5.579,3.702,9.27,3.702 c5.425,0,8.952-2.014,10.581-6.034l97.65-199.114c0.72-1.461,1.084-3.107,1.084-4.936 C312.577,153.031,311.146,150.104,308.288,147.725z"/> <path d="M217.653,163.632c-6.874-5.665-16.271-8.502-28.193-8.502c-11.924,0-21.285,2.837-28.088,8.502 c-6.803,5.67-10.203,14.63-10.203,26.878v39.768c0,12.252,3.399,21.212,10.203,26.878c6.801,5.67,16.164,8.502,28.088,8.502 c11.922,0,21.32-2.833,28.193-8.502c6.874-5.665,10.31-14.625,10.31-26.878V190.51 C227.963,178.262,224.526,169.302,217.653,163.632z M205.199,230.278c0,9.873-5.259,14.81-15.77,14.81 c-10.332,0-15.494-4.937-15.494-14.81V190.51c0-9.874,5.162-14.81,15.494-14.81c10.511,0,15.77,4.936,15.77,14.81V230.278z"/> <path d="M340.248,254.413c-6.874-5.666-16.271-8.503-28.193-8.503s-21.285,2.837-28.088,8.503 c-6.803,5.67-10.203,14.63-10.203,26.878v39.768c0,23.587,12.754,35.38,38.258,35.38c11.758,0,21.119-2.833,28.088-8.502 c6.964-5.666,10.447-14.626,10.447-26.878V281.29C350.558,269.044,347.122,260.083,340.248,254.413z M327.794,321.058 c0,9.874-5.257,14.81-15.77,14.81c-10.332,0-15.494-4.937-15.494-14.81V281.29c0-9.874,5.162-14.81,15.494-14.81 c10.513,0,15.77,4.937,15.77,14.81V321.058z"/> <path d="M437.019,74.981C388.667,26.629,324.38,0,256,0S123.332,26.629,74.98,74.981C26.628,123.333,0,187.621,0,256 s26.628,132.667,74.98,181.019C123.332,485.371,187.619,512,256,512s132.668-26.628,181.019-74.98S512,324.38,512,256 S485.371,123.333,437.019,74.981z M415.754,415.755c-42.672,42.672-99.408,66.173-159.755,66.173s-117.083-23.501-159.754-66.173 C53.572,373.083,30.073,316.348,30.073,256c0-60.348,23.5-117.083,66.173-159.755C138.917,53.574,195.653,30.073,256,30.073 s117.083,23.501,159.755,66.173c42.672,42.672,66.173,99.407,66.173,159.755C481.927,316.348,458.427,373.083,415.754,415.755z"/> </svg>
                                    </i>
                                special offers
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Wine Banner Two

![homepage-section](img/section-wine-banner-two.png)

---

* **HTML Content:**

```html
{{#block "feellio-wine-banner-two"}}
<div class="chiara-section feellio-section--wineBannerTwo">
    <div class="wineBannerTwo wow fadeIn">
        <div class="feellioWineBannerTwo-img">
            <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/wine-banner-02.jpg" alt="wine-banner-02.jpg">
        </div>
        <div class="container tm-inview" data-movement="-30">
            <div class="wineBannerTwo-content--left">
                <h4 class="feellioWineBannerTwo-title">drinks</h4>
                <div class="feellioWineBannerTwo-desc">BERECHE ET <br>LFILS BRUTL <br>RESERVE</div>
                <a href="#" class="feellioWineBannerTwo-link"><i class="icon"><svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 476.213 476.213" xml:space="preserve"> <polygon points="345.606,107.5 324.394,128.713 418.787,223.107 0,223.107 0,253.107 418.787,253.107 324.394,347.5 345.606,368.713 476.213,238.106 "/> </svg></i></a>
            </div>
            <div class="wineBannerTwo-content--right">
                <div class="wineBannerTwo-content-right-top">
                    <h4 class="feellioWineBannerTwo-title">vodka <br>tropical</h4>
                    <a href="#" class="feellioWineBannerTwo-link"><span>read more</span> <i class="icon"><svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 476.213 476.213" xml:space="preserve"> <polygon points="345.606,107.5 324.394,128.713 418.787,223.107 0,223.107 0,253.107 418.787,253.107 324.394,347.5 345.606,368.713 476.213,238.106 "/> </svg></i></a>
                </div>
                <div class="wineBannerTwo-content-right-bottom">
                    <div class="feellioWineBannerTwo-list">
                        <h5 class="feellioWineBannerTwo-list-title">material</h5>
                        <ul>
                            <li>4 cl NO.1 Vodka Tropical</li>
                            <li>Fanta Mango</li>
                            <li>2 cl syrup</li>
                            <li>3 cl lime juice</li>
                        </ul>
                    </div>
                    <div class="feellioWineBannerTwo-list">
                        <h5 class="feellioWineBannerTwo-list-title">preparation </h5>
                        <p>Pour NO.1 Vodka Tropical, Syrup 	&amp; lime juice into a glass filled with ice. Top up with Fanta Mango.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Wine Banner

![homepage-section](img/section-wine-banner.png)

---

* **HTML Content:**

```html
{{#block "feellio-wine-banner"}}
<div class="chiara-section feellio-section--wineBanner">
    <div class="feellioWineBanner wow fadeIn">
        <div class="feellioWineBanner-img">
                <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/wine-banner-1.jpg" alt="wine-banner-1.jpg">
        </div>
        <div class="container">
            <div class="feellioWineBanner-nav">
                    <div class="feellioWineMenu">
                            <div class="feellioWineMenu-item">
                                <a href="#">
                                    <i class="icon">
                                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve"> <path d="M188.275,157.013V8.533c0-4.71-3.823-8.533-8.533-8.533h-51.2c-4.71,0-8.533,3.823-8.533,8.533v148.48 c-31.727,17.954-51.209,51.2-51.2,87.979v258.475c0,4.719,3.823,8.533,8.533,8.533h153.6c4.71,0,8.533-3.814,8.533-8.533V245.001 C239.483,208.213,220.002,174.967,188.275,157.013z M222.408,494.933H85.875V244.992c-0.017-32.06,17.801-60.885,46.481-75.221 c2.893-1.451,4.719-4.403,4.719-7.637V17.067h34.133v145.067c0,3.234,1.826,6.195,4.719,7.637 c28.681,14.327,46.49,43.153,46.481,75.221V494.933z"/> <rect x="128.516" y="42.667" width="51.2" height="17.067"/> <path d="M442.397,276.207l-15.275-106.752c-0.597-4.198-4.198-7.322-8.448-7.322h-102.4c-4.241,0-7.842,3.123-8.456,7.322 l-15.266,106.283c-1.451,9.728-0.922,19.482,1.502,28.817l1.485,6.255c8.277,33.041,37.854,56.115,71.919,56.124 c0.051,0,0.085,0,0.128,0c33.843,0,63.369-22.869,71.851-55.808l1.399-5.956C443.319,295.646,443.839,285.884,442.397,276.207z M424.281,301.056l-1.408,5.973c-6.502,25.233-29.227,42.837-55.287,42.837c-0.043,0-0.077,0-0.111,0 c-26.232,0-49.007-17.766-55.347-43.093l-1.502-6.332c-1.903-7.279-2.295-14.746-1.178-22.229l14.217-99.012h87.612l14.242,99.473 C426.628,286.114,426.235,293.581,424.281,301.056z"/> <rect x="358.916" y="358.4" width="17.067" height="110.933"/> <path d="M384.541,460.8h-34.133c-23.526,0-42.667,19.14-42.667,42.667c0,4.719,3.814,8.533,8.533,8.533h102.4 c4.719,0,8.533-3.814,8.533-8.533C427.208,479.94,408.068,460.8,384.541,460.8z M326.267,494.933 c3.524-9.933,13.022-17.067,24.141-17.067h34.133c11.127,0,20.617,7.134,24.141,17.067H326.267z"/> <rect x="299.182" y="281.6" width="136.533" height="17.067"/> <rect x="128.516" y="119.467" width="51.2" height="17.067"/> <path d="M196.808,264.533h-85.333c-4.71,0-8.533,3.814-8.533,8.533v153.6c0,4.719,3.823,8.533,8.533,8.533h85.333 c4.71,0,8.533-3.814,8.533-8.533v-153.6C205.341,268.348,201.518,264.533,196.808,264.533z M188.275,418.133h-68.267V281.6h68.267 V418.133z"/> </svg>
                                    </i>
                                mezcal
                                </a>
                            </div>
                            <div class="feellioWineMenu-item">
                                <a href="#">
                                    <i class="icon">
                                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 478.591 478.591" style="enable-background:new 0 0 478.591 478.591;" xml:space="preserve"> <path d="M256.095,222.631c-0.266-0.027-0.533-0.04-0.8-0.04h-90.152l-16.128-50.512c-5.129-19.418-16.004-36.835-31.2-49.968 c-12.765-11.036-21.9-25.669-26.208-41.984L72.015,5.943c-0.544-2.049-1.879-3.799-3.712-4.864 c-1.835-1.071-4.023-1.359-6.072-0.8L23.559,10.471c-4.271,1.129-6.819,5.508-5.689,9.779c0,0.002,0.001,0.003,0.001,0.005 l19.6,74.184c4.321,16.309,3.61,33.543-2.04,49.44c-6.712,18.816-7.596,39.218-2.536,58.544l4.456,20.168H15.295 c-2.305,0-4.497,0.995-6.016,2.728c-1.52,1.735-2.217,4.042-1.912,6.328l32,240c0.529,3.974,3.919,6.943,7.928,6.944h184 c4.109,0,7.549-3.112,7.96-7.2l24-240C263.697,226.995,260.491,223.073,256.095,222.631z M133.695,176.551l-0.04-0.032 l14.688,46.072H92.711l-10.952-27.384l51.648-19.36C133.479,176.087,133.591,176.311,133.695,176.551z M70.543,63.023l5.6,21.2 c5.132,19.417,16.006,36.833,31.2,49.968c8.498,7.448,15.4,16.54,20.288,26.728l-59.152,22.176 c-4.137,1.552-6.232,6.164-4.679,10.301c0.021,0.055,0.042,0.109,0.063,0.163l11.616,29.032H53.695l-5.264-23.936 c-4.309-16.317-3.59-33.555,2.064-49.456c6.711-18.926,7.548-39.438,2.4-58.848l-5.6-21.512L70.543,63.023z M35.391,23.895 l23.2-6.128l7.904,29.792l-23.288,5.816L35.391,23.895z M224.095,462.591H54.303l-29.864-224h222.056L224.095,462.591z"/> <path d="M367.295,350.591v-136c0-4.418-3.582-8-8-8h-80c-4.418,0-8,3.582-8,8v136c0.043,23.397,16.934,43.361,40,47.28v64.72h-32 c-4.418,0-8,3.582-8,8s3.582,8,8,8h80c4.418,0,8-3.582,8-8s-3.582-8-8-8h-32v-64.72 C350.361,393.952,367.251,373.988,367.295,350.591z M287.295,222.591h64v24h-64V222.591z M319.295,382.591 c-17.673,0-32-14.327-32-32v-88h64v88C351.295,368.264,336.968,382.591,319.295,382.591z"/> <path d="M471.295,350.591v-136c0-4.418-3.582-8-8-8h-80c-4.418,0-8,3.582-8,8v136c0.043,23.397,16.934,43.361,40,47.28v64.72h-32 c-4.418,0-8,3.582-8,8s3.582,8,8,8h80c4.418,0,8-3.582,8-8s-3.582-8-8-8h-32v-64.72 C454.361,393.952,471.251,373.988,471.295,350.591z M391.295,222.591h64v24h-64V222.591z M423.295,382.591 c-17.673,0-32-14.327-32-32v-88h64v88C455.295,368.264,440.968,382.591,423.295,382.591z"/> </svg>
                                    </i>
                                champagne
                                </a>
                            </div>
                            <div class="feellioWineMenu-item">
                                <a href="#">
                                    <i class="icon">
                                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 19.86 19.86" style="enable-background:new 0 0 19.86 19.86;" xml:space="preserve" > <path d="M13.299,15.84c-0.001-0.143-0.002-0.283-0.004-0.419c-0.024-1.808-0.124-2.97-0.188-3.716 c-0.001-0.014-0.002-0.028-0.004-0.041l-0.03-0.354c-0.001-0.008-0.003-0.018-0.003-0.024c-0.04-0.406-0.333-1.498-0.704-2.88 c-0.525-1.954-1.404-5.227-1.204-5.625c0.406-0.513,0.216-1.025,0.015-1.287c0.024-0.19,0.061-0.619-0.015-1 C11.071,0.045,10.02,0,10.01,0C9.98,0,9.953,0.002,9.93,0.004C9.906,0.002,9.879,0,9.85,0C9.839,0,8.789,0.045,8.699,0.494 c-0.076,0.381-0.039,0.81-0.015,1c-0.201,0.262-0.392,0.773,0.01,1.28C8.899,3.179,8.02,6.452,7.495,8.407 c-0.371,1.381-0.664,2.473-0.704,2.88c-0.001,0.007-0.003,0.018-0.003,0.023l-0.03,0.354c-0.001,0.013-0.002,0.028-0.004,0.041 c-0.065,0.746-0.164,1.905-0.189,3.716c-0.002,0.137-0.003,0.275-0.004,0.419c-0.006,0.858,0.004,1.847,0.041,2.997 c0.02,0.212,0.078,0.848,2.759,0.999c0,0,0.384,0.028,0.564,0.022c0.19,0.005,0.585-0.023,0.585-0.023 c2.671-0.152,2.729-0.787,2.75-1.011C13.295,17.68,13.306,16.695,13.299,15.84z M9.095,0.612c0.067-0.075,0.476-0.19,0.792-0.19 c0.003,0,0.007,0,0.01,0l0.08,0.003l0.033-0.006c0.271,0,0.688,0.117,0.741,0.157c0.047,0.234,0.041,0.496,0.027,0.686H9.081 C9.065,1.076,9.057,0.824,9.095,0.612z M9.027,2.521c-0.331-0.419-0.01-0.779,0.027-0.817L9.078,1.68h1.704l0.024,0.025 c0.015,0.015,0.368,0.385,0.027,0.816c-0.272,0.344-0.007,1.691,0.771,4.652h-0.236c-0.129-0.501-0.713-0.87-1.438-0.87 S8.62,6.671,8.491,7.173H8.257C9.034,4.212,9.299,2.865,9.027,2.521z M7.9,8.516c0.087-0.325,0.168-0.63,0.247-0.925h0.346 c0.129,0.502,0.713,0.87,1.438,0.87s1.309-0.369,1.438-0.87h0.346c0.077,0.296,0.158,0.6,0.245,0.925 c0.328,1.22,0.636,2.366,0.687,2.771H7.214C7.264,10.883,7.572,9.736,7.9,8.516z M12.841,18.799 c-0.017,0.191-0.573,0.538-2.55,0.629l-0.126,0.018c-0.062,0-0.143-0.002-0.239-0.004c-0.057,0.002-0.109,0.002-0.155,0.004 l-0.2-0.018c-1.976-0.091-2.533-0.438-2.549-0.615c-0.036-1.141-0.046-2.121-0.04-2.972h5.9 C12.887,16.688,12.877,17.665,12.841,18.799z"/> </svg>
                                    </i>
                                rose
                                </a>
                            </div>
                            <div class="feellioWineMenu-item">
                                <a href="#">
                                    <i class="icon">
                                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 150 150"><path d="M102,8.17H60.32a8.51,8.51,0,0,0-8.5,8.5v4a8.52,8.52,0,0,0,8.5,8.5H79.16V63h4V29.17H102a8.51,8.51,0,0,0,8.5-8.5v-4A8.51,8.51,0,0,0,102,8.17Zm5.5,12.5a5.51,5.51,0,0,1-5.5,5.5H60.32a5.51,5.51,0,0,1-5.5-5.5v-4a5.5,5.5,0,0,1,5.5-5.5H102a5.5,5.5,0,0,1,5.5,5.5Z"/><path d="M93.91,113.73v-23A5.66,5.66,0,0,0,98,85.36V79.14a5.83,5.83,0,0,0-6-5.64H71.68a5.83,5.83,0,0,0-6,5.64v6.22a5.72,5.72,0,0,0,4.49,5.46l.41.09v21.85A28.81,28.81,0,0,0,52.41,139.5c0,.2,0,.41,0,.6l.09,1.4H109.8l.09-1.4a5.93,5.93,0,0,0,0-.6A28.82,28.82,0,0,0,93.91,113.73ZM68.68,85.36V79.14a2.84,2.84,0,0,1,3-2.64H92a2.84,2.84,0,0,1,3,2.64v6.22a2.7,2.7,0,0,1-2,2.5A3.43,3.43,0,0,1,92,88H71.68a3.27,3.27,0,0,1-.78-.09A2.75,2.75,0,0,1,68.68,85.36ZM55.43,138.5a25.79,25.79,0,0,1,17.15-23.29l1-.35V91.5H90.91v24.15l.88.4a25.8,25.8,0,0,1,15.1,22.45Z"/></svg>
                                    </i>
                                accessories
                                </a>
                            </div>
                            <div class="feellioWineMenu-item">
                                <a href="#">
                                    <i class="icon">
                                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve"> <path d="M308.288,147.725c-2.859-2.375-6.038-3.566-9.544-3.566c-4.521,0-7.773,1.921-9.762,5.76l-97.641,199.936 c-0.725,1.83-1.085,3.385-1.085,4.662c0,3.107,1.243,5.896,3.736,8.365c2.49,2.468,5.579,3.702,9.27,3.702 c5.425,0,8.952-2.014,10.581-6.034l97.65-199.114c0.72-1.461,1.084-3.107,1.084-4.936 C312.577,153.031,311.146,150.104,308.288,147.725z"/> <path d="M217.653,163.632c-6.874-5.665-16.271-8.502-28.193-8.502c-11.924,0-21.285,2.837-28.088,8.502 c-6.803,5.67-10.203,14.63-10.203,26.878v39.768c0,12.252,3.399,21.212,10.203,26.878c6.801,5.67,16.164,8.502,28.088,8.502 c11.922,0,21.32-2.833,28.193-8.502c6.874-5.665,10.31-14.625,10.31-26.878V190.51 C227.963,178.262,224.526,169.302,217.653,163.632z M205.199,230.278c0,9.873-5.259,14.81-15.77,14.81 c-10.332,0-15.494-4.937-15.494-14.81V190.51c0-9.874,5.162-14.81,15.494-14.81c10.511,0,15.77,4.936,15.77,14.81V230.278z"/> <path d="M340.248,254.413c-6.874-5.666-16.271-8.503-28.193-8.503s-21.285,2.837-28.088,8.503 c-6.803,5.67-10.203,14.63-10.203,26.878v39.768c0,23.587,12.754,35.38,38.258,35.38c11.758,0,21.119-2.833,28.088-8.502 c6.964-5.666,10.447-14.626,10.447-26.878V281.29C350.558,269.044,347.122,260.083,340.248,254.413z M327.794,321.058 c0,9.874-5.257,14.81-15.77,14.81c-10.332,0-15.494-4.937-15.494-14.81V281.29c0-9.874,5.162-14.81,15.494-14.81 c10.513,0,15.77,4.937,15.77,14.81V321.058z"/> <path d="M437.019,74.981C388.667,26.629,324.38,0,256,0S123.332,26.629,74.98,74.981C26.628,123.333,0,187.621,0,256 s26.628,132.667,74.98,181.019C123.332,485.371,187.619,512,256,512s132.668-26.628,181.019-74.98S512,324.38,512,256 S485.371,123.333,437.019,74.981z M415.754,415.755c-42.672,42.672-99.408,66.173-159.755,66.173s-117.083-23.501-159.754-66.173 C53.572,373.083,30.073,316.348,30.073,256c0-60.348,23.5-117.083,66.173-159.755C138.917,53.574,195.653,30.073,256,30.073 s117.083,23.501,159.755,66.173c42.672,42.672,66.173,99.407,66.173,159.755C481.927,316.348,458.427,373.083,415.754,415.755z"/> </svg>
                                    </i>
                                special offers
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Wine Blog

![homepage-section](img/section-wine-blog.png)

---

* **HTML Content:**

```html
{{#block "feellio-wine-blog"}}
<div class="chiara-section feellio-section--wineBlog">
    <div class="feellioWineBlog">
        <div class="feellioWine-section-heading wow fadeIn">
            <span class="feellioWine-section-heading-top">PRODUCTS</span>
            <h3 class="feellioWine-section-heading-main page-heading">BLOG UPDATES</h3>
            <p class="feellioWine-section-heading-sub">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim venia</p>
        </div>
        <div class="container">
            <div class="feellioWineBlog-blog">
                <ul class="feellioWineBlog-posts">
                    {{#each blog.recent_posts}}
                        <li class="feellioWineBlog-posts-item">
                            <div class="feellioWineBlog-posts-image tm-inview" data-movement="-30">
                                {{#if thumbnail}}
                                        <a href="{{url}}">
                                            <img class="lazyload" data-sizes="auto" src="{{cdn 'img/loading.svg'}}" data-src="{{#if large_image}}{{getImage thumbnail 'blog_post_size'}}{{else}}{{getImage thumbnail 'blog_size'}}{{/if}}" alt="{{thumbnail.alt}}" title="{{thumbnail.alt}}">
                                        </a>
                                {{/if}}
                            </div>
                            <div class="feellioWineBlog-posts-content">
                                <div class="feellioWineBlog-post-date" data-moment-input-format="MMM D">{{date_published}}</div>
                                <h4 class="feellioWineBlog-post-title"><a href="{{url}}">{{title}}</a></h4>
                                <div class="feellioWineBlog-post-summary">{{{summary}}}</div>
                                <a class="feellioWineBlog-post-link" href="{{url}}">Continue <i class="icon"><svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 476.213 476.213" xml:space="preserve"> <polygon points="345.606,107.5 324.394,128.713 418.787,223.107 0,223.107 0,253.107 418.787,253.107 324.394,347.5 345.606,368.713 476.213,238.106 "/> </svg></i></a>
                            </div>
                        </li>
                    {{/each}}
                </ul>
                <div class="feellioWineBlog-posts-view-all">
                    <a class="feellioWineBlog-posts-view-all-link" href="{{blog.url}}" title="{{blog.name}}">read entire posts</a>
                </div>
                
            </div>
        </div>
    </div>
</div>
{{/block}}

```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Wine Info

![homepage-section](img/section-wine-info.png)

---

* **HTML Content:**

```html
{{#block "feellio-wine-info"}}
<div class="chiara-section feellio-section--wineInfo">
    <div class="container">
        <div class="feellioWineInfo">
            <div class="feellioWineInfo-item">
                <div class="feellioWineInfo-phone">
                    <i class="feellioWineInfo-icon">
                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 508.52 508.52" xml:space="preserve"> <path d="M476.737,317.825V254.26c0-146.072-111.906-222.477-222.477-222.477 c-107.87,0-222.477,77.962-222.477,222.477v63.565C14.239,317.825,0,332.063,0,349.607v63.565 c0,17.544,14.239,31.783,31.782,31.783c0,17.544,14.239,31.782,31.782,31.782s31.782-14.239,31.782-31.782v-127.13 c0-17.544-14.239-31.782-31.782-31.782V254.26c0-125.191,95.951-190.695,190.695-190.695c91.883,0,190.695,59.656,190.695,190.695 v31.782c-17.544,0-31.783,14.239-31.783,31.782v127.13c0,17.544,14.239,31.782,31.783,31.782 c17.544,0,31.782-14.239,31.782-31.782c17.544,0,31.782-14.239,31.782-31.783v-63.565 C508.52,332.063,494.281,317.825,476.737,317.825z"/> </svg>
                    </i>
                    <span>+(84) 123 456 7890</span>
                </div>
            </div>
            <div class="feellioWineInfo-item">
                <div class="feellioWineInfo-calendar">
                    <i class="feellioWineInfo-icon">
                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 485.213 485.212" xml:space="preserve"> <path d="M60.652,75.816V15.163C60.652,6.781,67.433,0,75.817,0c8.38,0,15.161,6.781,15.161,15.163v60.653 c0,8.38-6.781,15.161-15.161,15.161C67.433,90.978,60.652,84.196,60.652,75.816z M318.424,90.978 c8.378,0,15.163-6.781,15.163-15.161V15.163C333.587,6.781,326.802,0,318.424,0c-8.382,0-15.168,6.781-15.168,15.163v60.653 C303.256,84.196,310.042,90.978,318.424,90.978z M485.212,363.906c0,66.996-54.312,121.307-121.303,121.307 c-66.986,0-121.302-54.311-121.302-121.307c0-66.986,54.315-121.3,121.302-121.3C430.9,242.606,485.212,296.919,485.212,363.906z M454.89,363.906c0-50.161-40.81-90.976-90.98-90.976c-50.166,0-90.976,40.814-90.976,90.976c0,50.171,40.81,90.98,90.976,90.98 C414.08,454.886,454.89,414.077,454.89,363.906z M121.305,181.955H60.652v60.651h60.653V181.955z M60.652,333.584h60.653V272.93 H60.652V333.584z M151.629,242.606h60.654v-60.651h-60.654V242.606z M151.629,333.584h60.654V272.93h-60.654V333.584z M30.328,360.891V151.628h333.582v60.653h30.327V94c0-18.421-14.692-33.349-32.843-33.349h-12.647v15.166 c0,16.701-13.596,30.325-30.322,30.325c-16.731,0-30.326-13.624-30.326-30.325V60.651H106.14v15.166 c0,16.701-13.593,30.325-30.322,30.325c-16.733,0-30.327-13.624-30.327-30.325V60.651H32.859C14.707,60.651,0.001,75.579,0.001,94 v266.892c0,18.36,14.706,33.346,32.858,33.346h179.424v-30.331H32.859C31.485,363.906,30.328,362.487,30.328,360.891z M303.256,242.606v-60.651h-60.648v60.651H303.256z M409.399,363.906h-45.49v-45.49c0-8.377-6.781-15.158-15.163-15.158 s-15.159,6.781-15.159,15.158v60.658c0,8.378,6.777,15.163,15.159,15.163h60.653c8.382,0,15.163-6.785,15.163-15.163 C424.562,370.692,417.781,363.906,409.399,363.906z"/> </svg>
                    </i>
                    <span>Mon - sun:  9am - 10pm</span>
                </div>
            </div>
            <div class="feellioWineInfo-item">
                <div class="feellioWineInfo-follow">
                    <i class="feellioWineInfo-icon">
                        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" xml:space="preserve"> <path d="M492,127.5h-18v-18c0-11.046-8.954-20-20-20c-11.046,0-20,8.954-20,20v18h-18c-11.046,0-20,8.954-20,20s8.954,20,20,20 h18v18c0,11.046,8.954,20,20,20c11.046,0,20-8.954,20-20v-18h18c11.046,0,20-8.954,20-20S503.046,127.5,492,127.5z"/> <path d="M315.409,249.231C345.854,225.711,365.5,188.86,365.5,147.5C365.5,76.645,307.855,19,237,19S108.5,76.645,108.5,147.5 c0,41.359,19.646,78.211,50.091,101.731C68.293,280.793,0,367.427,0,473c0,11.046,8.954,20,20,20h434c11.046,0,20-8.954,20-20 C474,367.401,405.656,280.775,315.409,249.231z M148.5,147.5c0-48.799,39.701-88.5,88.5-88.5s88.5,39.701,88.5,88.5 S285.799,236,237,236S148.5,196.299,148.5,147.5z M41.008,453C51.061,353.73,135.123,276,237,276s185.939,77.73,195.992,177 H41.008z"/> </svg>
                    </i>
                    <ul>
                        <li>
                            <a href="#"><svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" xml:space="preserve"> <polygon points="448,224 448,160 416,160 416,224 352,224 352,256 416,256 416,320 448,320 448,256 512,256 512,224 "/> <path d="M160,224v64h90.528c-13.216,37.248-48.8,64-90.528,64c-52.928,0-96-43.072-96-96c0-52.928,43.072-96,96-96 c22.944,0,45.024,8.224,62.176,23.168l42.048-48.256C235.424,109.824,198.432,96,160,96C71.776,96,0,167.776,0,256 s71.776,160,160,160s160-71.776,160-160v-32H160z"/> </svg></a>
                        </li>
                        <li>
                            <a href="#"><svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 310.05 310.05" xml:space="preserve"> <path id="XMLID_799_" d="M245.265,31.772C223.923,11.284,194.388,0,162.101,0c-49.32,0-79.654,20.217-96.416,37.176 c-20.658,20.9-32.504,48.651-32.504,76.139c0,34.513,14.436,61.003,38.611,70.858c1.623,0.665,3.256,1,4.857,1 c5.1,0,9.141-3.337,10.541-8.69c0.816-3.071,2.707-10.647,3.529-13.936c1.76-6.495,0.338-9.619-3.5-14.142 c-6.992-8.273-10.248-18.056-10.248-30.788c0-37.818,28.16-78.011,80.352-78.011c41.412,0,67.137,23.537,67.137,61.425 c0,23.909-5.15,46.051-14.504,62.35c-6.5,11.325-17.93,24.825-35.477,24.825c-7.588,0-14.404-3.117-18.705-8.551 c-4.063-5.137-5.402-11.773-3.768-18.689c1.846-7.814,4.363-15.965,6.799-23.845c4.443-14.392,8.643-27.985,8.643-38.83 c0-18.55-11.404-31.014-28.375-31.014c-21.568,0-38.465,21.906-38.465,49.871c0,13.715,3.645,23.973,5.295,27.912 c-2.717,11.512-18.865,79.953-21.928,92.859c-1.771,7.534-12.44,67.039,5.219,71.784c19.841,5.331,37.576-52.623,39.381-59.172 c1.463-5.326,6.582-25.465,9.719-37.845c9.578,9.226,25,15.463,40.006,15.463c28.289,0,53.73-12.73,71.637-35.843 c17.367-22.418,26.932-53.664,26.932-87.978C276.869,77.502,265.349,51.056,245.265,31.772z"/> </svg></a>
                        </li>
                        <li>
                            <a href="#"><svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 155.139 155.139" xml:space="preserve"> <path d="M89.584,155.139V84.378h23.742l3.562-27.585H89.584V39.184 c0-7.984,2.208-13.425,13.67-13.425l14.595-0.006V1.08C115.325,0.752,106.661,0,96.577,0C75.52,0,61.104,12.853,61.104,36.452 v20.341H37.29v27.585h23.814v70.761H89.584z"/> </svg></a>
                        </li>
                        <li>
                            <a href="#"><svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" xml:space="preserve"> <path d="M512,97.248c-19.04,8.352-39.328,13.888-60.48,16.576c21.76-12.992,38.368-33.408,46.176-58.016 c-20.288,12.096-42.688,20.64-66.56,25.408C411.872,60.704,384.416,48,354.464,48c-58.112,0-104.896,47.168-104.896,104.992 c0,8.32,0.704,16.32,2.432,23.936c-87.264-4.256-164.48-46.08-216.352-109.792c-9.056,15.712-14.368,33.696-14.368,53.056 c0,36.352,18.72,68.576,46.624,87.232c-16.864-0.32-33.408-5.216-47.424-12.928c0,0.32,0,0.736,0,1.152 c0,51.008,36.384,93.376,84.096,103.136c-8.544,2.336-17.856,3.456-27.52,3.456c-6.72,0-13.504-0.384-19.872-1.792 c13.6,41.568,52.192,72.128,98.08,73.12c-35.712,27.936-81.056,44.768-130.144,44.768c-8.608,0-16.864-0.384-25.12-1.44 C46.496,446.88,101.6,464,161.024,464c193.152,0,298.752-160,298.752-298.688c0-4.64-0.16-9.12-0.384-13.568 C480.224,136.96,497.728,118.496,512,97.248z"/> </svg></a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Wine New Collection

![homepage-section](img/section-wine-new-collection.png)

---

* **HTML Content:**

```html
{{#block "feellio-wine-new-collection"}}
<div class="chiara-section feellio-section--wineNewCollection">
    <div class="feellioWine-section-heading">
        <span class="feellioWine-section-heading-top">shop</span>
        <h3 class="feellioWine-section-heading-main page-heading">NEW COLLECTION</h3>
        <p class="feellioWine-section-heading-sub">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim venia</p>
    </div>
    <div class="container">
        <div class="wineNewCollection">
            <div class="wineNewCollection-item">
                <div class="wineNewCollection-content-left tm-inview" data-movement="-30">
                    <h4 class="wineNewCollection-title">Jacky Blot</h4>
                    <p class="wineNewCollection-desc">There’s lovely energy and balance, with precise acidity and length</p>
                    <a class="wineNewCollection-link" href="#" title="Jacky Blot">Read more</a>
                </div>
                <div class="wineNewCollection-info-img">
                    <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/wine-new-collection-01.jpg" alt="wine-new-collection-01.jpg">
                </div>
                <div class="wineNewCollection-content-right tm-inview" data-movement="-30">
                    <h5 class="wineNewCollection-info-title">ingredient:</h5>
                    <ul class="wineNewCollection-info-list">
                        <li>organic hops</li>
                        <li>yeast (responsible for fermentation)</li>
                        <li>water 95%</li>
                    </ul>
                    <ul class="wineNewCollection-info-list-icon">
                        <li>
                            <i class="icon"><svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 561.543 561.542" style="enable-background:new 0 0 561.543 561.542;" xml:space="preserve"> <path d="M268.527,123.612h-1.386v-20.336h1.386V123.612z M284.614,103.275h-1.381v20.336h1.381V103.275z M271.118,103.275h-0.698 v20.336h0.698V103.275z M285.875,103.275h-0.69v20.336h0.69V103.275z M281.733,103.275h-0.698v20.336h0.698V103.275z M278.323,103.275h-0.688v20.336h0.688V103.275z M274.233,103.275h-1.386v20.336h1.386V103.275z M280.284,103.275h-1.381v20.336 h1.381V103.275z M275.39,103.275h-0.698v20.336h0.698V103.275z M287.723,103.275h-0.695v20.336h0.695V103.275z M290.836,103.275 h-1.382v20.336h1.382V103.275z M291.988,103.275h-0.699v20.336h0.699V103.275z M358.546,213.549v332.182 c0,3.183-1.909,6.071-4.868,7.295c-0.83,0.345-21.029,8.517-73.963,8.517c-52.21,0-70.282-7.771-72.169-8.662 c-2.77-1.302-4.548-4.088-4.548-7.159V213.549c0-42.263,28.378-61.895,40.202-68.235V77.852c0-0.033-0.017-0.047-0.017-0.077V7.903 c0-4.371,3.538-7.903,7.906-7.903h55.368c4.368,0,7.901,3.533,7.901,7.903v56.609c0,0.033,0.019,0.056,0.019,0.082v80.301 C332.153,152.917,358.546,174.661,358.546,213.549z M259.006,56.679h39.544v-40.86h-39.544V56.679z M342.729,213.549 c0-42.552-38.331-55.634-38.719-55.758c-3.253-1.066-5.446-4.096-5.446-7.514V85.685h-39.542v64.592c0,3.255-1.984,6.17-5.015,7.36 c-1.404,0.565-35.188,14.657-35.188,55.912v326.464c7.771,2.096,26.236,5.718,60.898,5.718c35.11,0,54.666-3.715,63.011-5.862 V213.549z M322.95,282.499c4.378,0,7.91,3.537,7.91,7.915v115.165c0,4.373-3.532,7.906-7.91,7.906h-87.529 c-4.371,0-7.908-3.533-7.908-7.906V290.414c0-4.368,3.538-7.906,7.908-7.906h87.529V282.499z M315.044,298.325h-71.717v99.348 h71.717V298.325z"/> </svg></i>
                            <span>750ml</span>
                        </li>
                        <li>
                            <i class="icon"><svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve"> <path d="M308.288,147.725c-2.859-2.375-6.038-3.566-9.544-3.566c-4.521,0-7.773,1.921-9.762,5.76l-97.641,199.936 c-0.725,1.83-1.085,3.385-1.085,4.662c0,3.107,1.243,5.896,3.736,8.365c2.49,2.468,5.579,3.702,9.27,3.702 c5.425,0,8.952-2.014,10.581-6.034l97.65-199.114c0.72-1.461,1.084-3.107,1.084-4.936 C312.577,153.031,311.146,150.104,308.288,147.725z"/> <path d="M217.653,163.632c-6.874-5.665-16.271-8.502-28.193-8.502c-11.924,0-21.285,2.837-28.088,8.502 c-6.803,5.67-10.203,14.63-10.203,26.878v39.768c0,12.252,3.399,21.212,10.203,26.878c6.801,5.67,16.164,8.502,28.088,8.502 c11.922,0,21.32-2.833,28.193-8.502c6.874-5.665,10.31-14.625,10.31-26.878V190.51 C227.963,178.262,224.526,169.302,217.653,163.632z M205.199,230.278c0,9.873-5.259,14.81-15.77,14.81 c-10.332,0-15.494-4.937-15.494-14.81V190.51c0-9.874,5.162-14.81,15.494-14.81c10.511,0,15.77,4.936,15.77,14.81V230.278z"/> <path d="M340.248,254.413c-6.874-5.666-16.271-8.503-28.193-8.503s-21.285,2.837-28.088,8.503 c-6.803,5.67-10.203,14.63-10.203,26.878v39.768c0,23.587,12.754,35.38,38.258,35.38c11.758,0,21.119-2.833,28.088-8.502 c6.964-5.666,10.447-14.626,10.447-26.878V281.29C350.558,269.044,347.122,260.083,340.248,254.413z M327.794,321.058 c0,9.874-5.257,14.81-15.77,14.81c-10.332,0-15.494-4.937-15.494-14.81V281.29c0-9.874,5.162-14.81,15.494-14.81 c10.513,0,15.77,4.937,15.77,14.81V321.058z"/> <path d="M437.019,74.981C388.667,26.629,324.38,0,256,0S123.332,26.629,74.98,74.981C26.628,123.333,0,187.621,0,256 s26.628,132.667,74.98,181.019C123.332,485.371,187.619,512,256,512s132.668-26.628,181.019-74.98S512,324.38,512,256 S485.371,123.333,437.019,74.981z M415.754,415.755c-42.672,42.672-99.408,66.173-159.755,66.173s-117.083-23.501-159.754-66.173 C53.572,373.083,30.073,316.348,30.073,256c0-60.348,23.5-117.083,66.173-159.755C138.917,53.574,195.653,30.073,256,30.073 s117.083,23.501,159.755,66.173c42.672,42.672,66.173,99.407,66.173,159.755C481.927,316.348,458.427,373.083,415.754,415.755z"/> </svg></i>
                            <span>0.45Alc</span>
                        </li>
                        <li>
                            <i class="icon"><svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 50"><path d="M25,47.5A22.5,22.5,0,1,1,47.5,25,22.53,22.53,0,0,1,25,47.5Zm0-42A19.5,19.5,0,1,0,44.5,25,19.52,19.52,0,0,0,25,5.5Z"/><path d="M25,35.17A10.17,10.17,0,1,1,35.17,25,10.19,10.19,0,0,1,25,35.17Zm0-17.35A7.17,7.17,0,1,0,32.17,25,7.18,7.18,0,0,0,25,17.83Z"/></svg></i>
                            <span>GREEN</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="wineNewCollection-item">
                <div class="wineNewCollection-content-left tm-inview" data-movement="-30">
                    <h4 class="wineNewCollection-title">Varner Foxglove Zinfandel</h4>
                    <p class="wineNewCollection-desc">A great everyday Cali Pinot Noir with real depth and character that won’t break the bank.</p>
                    <a class="wineNewCollection-link" href="#" title="Jacky Blot">Read more</a>
                </div>
                <div class="wineNewCollection-info-img">
                    <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/wine-new-collection-02.jpg" alt="wine-new-collection-02.jpg">
                </div>
                <div class="wineNewCollection-content-right tm-inview" data-movement="-30">
                    <h5 class="wineNewCollection-info-title">ingredient:</h5>
                    <ul class="wineNewCollection-info-list">
                        <li>organic hops</li>
                        <li>Young 2018 - 2028</li>
                        <li>water 95%</li>
                        <li>Critic score 95/100</li>
                    </ul>
                    <ul class="wineNewCollection-info-list-icon">
                        <li>
                            <i class="icon"><svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 561.543 561.542" style="enable-background:new 0 0 561.543 561.542;" xml:space="preserve"> <path d="M268.527,123.612h-1.386v-20.336h1.386V123.612z M284.614,103.275h-1.381v20.336h1.381V103.275z M271.118,103.275h-0.698 v20.336h0.698V103.275z M285.875,103.275h-0.69v20.336h0.69V103.275z M281.733,103.275h-0.698v20.336h0.698V103.275z M278.323,103.275h-0.688v20.336h0.688V103.275z M274.233,103.275h-1.386v20.336h1.386V103.275z M280.284,103.275h-1.381v20.336 h1.381V103.275z M275.39,103.275h-0.698v20.336h0.698V103.275z M287.723,103.275h-0.695v20.336h0.695V103.275z M290.836,103.275 h-1.382v20.336h1.382V103.275z M291.988,103.275h-0.699v20.336h0.699V103.275z M358.546,213.549v332.182 c0,3.183-1.909,6.071-4.868,7.295c-0.83,0.345-21.029,8.517-73.963,8.517c-52.21,0-70.282-7.771-72.169-8.662 c-2.77-1.302-4.548-4.088-4.548-7.159V213.549c0-42.263,28.378-61.895,40.202-68.235V77.852c0-0.033-0.017-0.047-0.017-0.077V7.903 c0-4.371,3.538-7.903,7.906-7.903h55.368c4.368,0,7.901,3.533,7.901,7.903v56.609c0,0.033,0.019,0.056,0.019,0.082v80.301 C332.153,152.917,358.546,174.661,358.546,213.549z M259.006,56.679h39.544v-40.86h-39.544V56.679z M342.729,213.549 c0-42.552-38.331-55.634-38.719-55.758c-3.253-1.066-5.446-4.096-5.446-7.514V85.685h-39.542v64.592c0,3.255-1.984,6.17-5.015,7.36 c-1.404,0.565-35.188,14.657-35.188,55.912v326.464c7.771,2.096,26.236,5.718,60.898,5.718c35.11,0,54.666-3.715,63.011-5.862 V213.549z M322.95,282.499c4.378,0,7.91,3.537,7.91,7.915v115.165c0,4.373-3.532,7.906-7.91,7.906h-87.529 c-4.371,0-7.908-3.533-7.908-7.906V290.414c0-4.368,3.538-7.906,7.908-7.906h87.529V282.499z M315.044,298.325h-71.717v99.348 h71.717V298.325z"/> </svg></i>
                            <span>750ml</span>
                        </li>
                        <li>
                            <i class="icon"><svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve"> <path d="M308.288,147.725c-2.859-2.375-6.038-3.566-9.544-3.566c-4.521,0-7.773,1.921-9.762,5.76l-97.641,199.936 c-0.725,1.83-1.085,3.385-1.085,4.662c0,3.107,1.243,5.896,3.736,8.365c2.49,2.468,5.579,3.702,9.27,3.702 c5.425,0,8.952-2.014,10.581-6.034l97.65-199.114c0.72-1.461,1.084-3.107,1.084-4.936 C312.577,153.031,311.146,150.104,308.288,147.725z"/> <path d="M217.653,163.632c-6.874-5.665-16.271-8.502-28.193-8.502c-11.924,0-21.285,2.837-28.088,8.502 c-6.803,5.67-10.203,14.63-10.203,26.878v39.768c0,12.252,3.399,21.212,10.203,26.878c6.801,5.67,16.164,8.502,28.088,8.502 c11.922,0,21.32-2.833,28.193-8.502c6.874-5.665,10.31-14.625,10.31-26.878V190.51 C227.963,178.262,224.526,169.302,217.653,163.632z M205.199,230.278c0,9.873-5.259,14.81-15.77,14.81 c-10.332,0-15.494-4.937-15.494-14.81V190.51c0-9.874,5.162-14.81,15.494-14.81c10.511,0,15.77,4.936,15.77,14.81V230.278z"/> <path d="M340.248,254.413c-6.874-5.666-16.271-8.503-28.193-8.503s-21.285,2.837-28.088,8.503 c-6.803,5.67-10.203,14.63-10.203,26.878v39.768c0,23.587,12.754,35.38,38.258,35.38c11.758,0,21.119-2.833,28.088-8.502 c6.964-5.666,10.447-14.626,10.447-26.878V281.29C350.558,269.044,347.122,260.083,340.248,254.413z M327.794,321.058 c0,9.874-5.257,14.81-15.77,14.81c-10.332,0-15.494-4.937-15.494-14.81V281.29c0-9.874,5.162-14.81,15.494-14.81 c10.513,0,15.77,4.937,15.77,14.81V321.058z"/> <path d="M437.019,74.981C388.667,26.629,324.38,0,256,0S123.332,26.629,74.98,74.981C26.628,123.333,0,187.621,0,256 s26.628,132.667,74.98,181.019C123.332,485.371,187.619,512,256,512s132.668-26.628,181.019-74.98S512,324.38,512,256 S485.371,123.333,437.019,74.981z M415.754,415.755c-42.672,42.672-99.408,66.173-159.755,66.173s-117.083-23.501-159.754-66.173 C53.572,373.083,30.073,316.348,30.073,256c0-60.348,23.5-117.083,66.173-159.755C138.917,53.574,195.653,30.073,256,30.073 s117.083,23.501,159.755,66.173c42.672,42.672,66.173,99.407,66.173,159.755C481.927,316.348,458.427,373.083,415.754,415.755z"/> </svg></i>
                            <span>0.45Alc</span>
                        </li>
                        <li>
                            <i class="icon"><svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 50"><path d="M25,47.5A22.5,22.5,0,1,1,47.5,25,22.53,22.53,0,0,1,25,47.5Zm0-42A19.5,19.5,0,1,0,44.5,25,19.52,19.52,0,0,0,25,5.5Z"/><path d="M25,35.17A10.17,10.17,0,1,1,35.17,25,10.19,10.19,0,0,1,25,35.17Zm0-17.35A7.17,7.17,0,1,0,32.17,25,7.18,7.18,0,0,0,25,17.83Z"/></svg></i>
                            <span>GREEN</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="wineNewCollection-item">
                <div class="wineNewCollection-content-left tm-inview" data-movement="-30">
                    <h4 class="wineNewCollection-title">Grace Bridge Pinot Noir</h4>
                    <p class="wineNewCollection-desc">The Foxglove range is from Paso Robles in Central Coast, California.</p>
                    <a class="wineNewCollection-link" href="#" title="Jacky Blot">Read more</a>
                </div>
                <div class="wineNewCollection-info-img">
                    <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/wine-new-collection-03.jpg" alt="wine-new-collection-03.jpg">
                </div>
                <div class="wineNewCollection-content-right tm-inview" data-movement="-30">   
                    <h5 class="wineNewCollection-info-title">ingredient:</h5>
                    <ul class="wineNewCollection-info-list">
                        <li>organic hops</li>
                        <li>Darker, silky fruit and violets</li>
                        <li>water 95%</li>
                    </ul>
                    <ul class="wineNewCollection-info-list-icon">
                        <li>
                            <i class="icon"><svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 561.543 561.542" style="enable-background:new 0 0 561.543 561.542;" xml:space="preserve"> <path d="M268.527,123.612h-1.386v-20.336h1.386V123.612z M284.614,103.275h-1.381v20.336h1.381V103.275z M271.118,103.275h-0.698 v20.336h0.698V103.275z M285.875,103.275h-0.69v20.336h0.69V103.275z M281.733,103.275h-0.698v20.336h0.698V103.275z M278.323,103.275h-0.688v20.336h0.688V103.275z M274.233,103.275h-1.386v20.336h1.386V103.275z M280.284,103.275h-1.381v20.336 h1.381V103.275z M275.39,103.275h-0.698v20.336h0.698V103.275z M287.723,103.275h-0.695v20.336h0.695V103.275z M290.836,103.275 h-1.382v20.336h1.382V103.275z M291.988,103.275h-0.699v20.336h0.699V103.275z M358.546,213.549v332.182 c0,3.183-1.909,6.071-4.868,7.295c-0.83,0.345-21.029,8.517-73.963,8.517c-52.21,0-70.282-7.771-72.169-8.662 c-2.77-1.302-4.548-4.088-4.548-7.159V213.549c0-42.263,28.378-61.895,40.202-68.235V77.852c0-0.033-0.017-0.047-0.017-0.077V7.903 c0-4.371,3.538-7.903,7.906-7.903h55.368c4.368,0,7.901,3.533,7.901,7.903v56.609c0,0.033,0.019,0.056,0.019,0.082v80.301 C332.153,152.917,358.546,174.661,358.546,213.549z M259.006,56.679h39.544v-40.86h-39.544V56.679z M342.729,213.549 c0-42.552-38.331-55.634-38.719-55.758c-3.253-1.066-5.446-4.096-5.446-7.514V85.685h-39.542v64.592c0,3.255-1.984,6.17-5.015,7.36 c-1.404,0.565-35.188,14.657-35.188,55.912v326.464c7.771,2.096,26.236,5.718,60.898,5.718c35.11,0,54.666-3.715,63.011-5.862 V213.549z M322.95,282.499c4.378,0,7.91,3.537,7.91,7.915v115.165c0,4.373-3.532,7.906-7.91,7.906h-87.529 c-4.371,0-7.908-3.533-7.908-7.906V290.414c0-4.368,3.538-7.906,7.908-7.906h87.529V282.499z M315.044,298.325h-71.717v99.348 h71.717V298.325z"/> </svg></i>
                            <span>750ml</span>
                        </li>
                        <li>
                            <i class="icon"><svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve"> <path d="M308.288,147.725c-2.859-2.375-6.038-3.566-9.544-3.566c-4.521,0-7.773,1.921-9.762,5.76l-97.641,199.936 c-0.725,1.83-1.085,3.385-1.085,4.662c0,3.107,1.243,5.896,3.736,8.365c2.49,2.468,5.579,3.702,9.27,3.702 c5.425,0,8.952-2.014,10.581-6.034l97.65-199.114c0.72-1.461,1.084-3.107,1.084-4.936 C312.577,153.031,311.146,150.104,308.288,147.725z"/> <path d="M217.653,163.632c-6.874-5.665-16.271-8.502-28.193-8.502c-11.924,0-21.285,2.837-28.088,8.502 c-6.803,5.67-10.203,14.63-10.203,26.878v39.768c0,12.252,3.399,21.212,10.203,26.878c6.801,5.67,16.164,8.502,28.088,8.502 c11.922,0,21.32-2.833,28.193-8.502c6.874-5.665,10.31-14.625,10.31-26.878V190.51 C227.963,178.262,224.526,169.302,217.653,163.632z M205.199,230.278c0,9.873-5.259,14.81-15.77,14.81 c-10.332,0-15.494-4.937-15.494-14.81V190.51c0-9.874,5.162-14.81,15.494-14.81c10.511,0,15.77,4.936,15.77,14.81V230.278z"/> <path d="M340.248,254.413c-6.874-5.666-16.271-8.503-28.193-8.503s-21.285,2.837-28.088,8.503 c-6.803,5.67-10.203,14.63-10.203,26.878v39.768c0,23.587,12.754,35.38,38.258,35.38c11.758,0,21.119-2.833,28.088-8.502 c6.964-5.666,10.447-14.626,10.447-26.878V281.29C350.558,269.044,347.122,260.083,340.248,254.413z M327.794,321.058 c0,9.874-5.257,14.81-15.77,14.81c-10.332,0-15.494-4.937-15.494-14.81V281.29c0-9.874,5.162-14.81,15.494-14.81 c10.513,0,15.77,4.937,15.77,14.81V321.058z"/> <path d="M437.019,74.981C388.667,26.629,324.38,0,256,0S123.332,26.629,74.98,74.981C26.628,123.333,0,187.621,0,256 s26.628,132.667,74.98,181.019C123.332,485.371,187.619,512,256,512s132.668-26.628,181.019-74.98S512,324.38,512,256 S485.371,123.333,437.019,74.981z M415.754,415.755c-42.672,42.672-99.408,66.173-159.755,66.173s-117.083-23.501-159.754-66.173 C53.572,373.083,30.073,316.348,30.073,256c0-60.348,23.5-117.083,66.173-159.755C138.917,53.574,195.653,30.073,256,30.073 s117.083,23.501,159.755,66.173c42.672,42.672,66.173,99.407,66.173,159.755C481.927,316.348,458.427,373.083,415.754,415.755z"/> </svg></i>
                            <span>0.45Alc</span>
                        </li>
                        <li>
                            <i class="icon"><svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 50"><path d="M25,47.5A22.5,22.5,0,1,1,47.5,25,22.53,22.53,0,0,1,25,47.5Zm0-42A19.5,19.5,0,1,0,44.5,25,19.52,19.52,0,0,0,25,5.5Z"/><path d="M25,35.17A10.17,10.17,0,1,1,35.17,25,10.19,10.19,0,0,1,25,35.17Zm0-17.35A7.17,7.17,0,1,0,32.17,25,7.18,7.18,0,0,0,25,17.83Z"/></svg></i>
                            <span>GREEN</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Wine Top Product

![homepage-section](img/section-wine-top-product.png)

---

* **HTML Content:**

```html
{{#block "feellio-wine-top-product"}}
{{#if products.top_sellers}}
    <div class="chiara-section feellio-section--wineTopProducts">
        <div class="container">
            <div class="wineTopProducts">
                <div class="feellioWine-section-heading">
                    <span class="feellioWine-section-heading-top">shop</span>
                    <h3 class="feellioWine-section-heading-main page-heading">TOP PRODUCTS</h3>
                    <p class="feellioWine-section-heading-sub">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim venia</p>
                </div>
                {{> components/chiara/products/grid
                    products=products.top_sellers
                    columns=theme_settings.products_top_columns
                    columns_sm=theme_settings.products_top_columns_sm
                    columns_md=theme_settings.products_top_columns_md
                }}
                <div class="wineTopProducts-view-all">
                    <a class="wineTopProducts-view-all-link" href="#" title="View All">View All</a>
                </div>
            </div>
        </div>
    </div>
{{/if}}
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Bakery Banner Three

![homepage-section](img/section-bakery-banner-three.png)

---

* **HTML Content:**

```html
{{#block "feellio-bakery-banner-three"}}
<div class="chiara-section feellio-section--bakeryBannerThree">
    <div class="container">
        <div class="feellioBakeryBannerThree">
            <div class="feellioBakeryBannerThree-left">
                <div class="feellioBakeryBannerThree-banner">
                    <div class="feellioBakeryBannerThree-img"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-banner-three-01.jpg" alt="feelio-bakery-banner-three-01.jpg" /></a></div>
                    <div class="feellioBakeryBannerThree-body wow fadeIn tm-inview" data-wow-delay="200ms" data-movement="-30">
                        <h3 class="feellioBakeryBannerThree-title">Cookies</h3>
                        <ul class="feellioBakeryBannerThree-list">
                            <li><a href="#" class="feellioBakeryBannerThree-action">Macaroon</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Jumble</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Ladyfinger</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Chocolate chip</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Cracker</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Thumbprint cookie</a></li>
                        </ul>    
                    </div>
                </div>
                <div class="feellioBakeryBannerThree-banner">
                    <div class="feellioBakeryBannerThree-img"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-banner-three-02.jpg" alt="feelio-bakery-banner-three-02.jpg" /></a></div>
                    <div class="feellioBakeryBannerThree-body wow fadeIn tm-inview" data-wow-delay="200ms" data-movement="-30">
                        <h3 class="feellioBakeryBannerThree-title">Cake</h3>
                        <ul class="feellioBakeryBannerThree-list">
                            <li><a href="#" class="feellioBakeryBannerThree-action">Cupcake</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Angel food</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Muffins</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Devil food</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Chiffon</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Pound cake</a></li>
                        </ul>    
                    </div>
                </div>
            </div>
            <div class="feellioBakeryBannerThree-right">
                <div class="feellioBakeryBannerThree-banner">
                    <div class="feellioBakeryBannerThree-img"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-banner-three-03.jpg" alt="feelio-bakery-banner-three-03.jpg" /></a></div>
                    <div class="feellioBakeryBannerThree-body wow fadeIn tm-inview" data-wow-delay="200ms" data-movement="-30">
                        <h3 class="feellioBakeryBannerThree-title">Bread</h3>
                        <ul class="feellioBakeryBannerThree-list">
                            <li><a href="#" class="feellioBakeryBannerThree-action">Challah</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Pretzel</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Swiss roll</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">French bread</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Quick bread</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Croissant</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Loaf Bread</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Sandwich</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Wheat bread</a></li>
                            <li><a href="#" class="feellioBakeryBannerThree-action">Bread stick</a></li>
                        </ul>    
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Bakery Banner Four

![homepage-section](img/section-bakery-banner-four.png)

---

* **HTML Content:**

```html
{{#block "feellio-bakery-banner-four"}}
<div class="chiara-section feellio-section--bakeryBannerFour">
    <div class="feellioBakery-section-heading wow fadeIn">
        <div class="feellioBakery-section-heading-img"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-banner-four-heading.jpg" alt="feelio-bakery-banner-four-heading.jpg" /></div>
        <h3 class="feellioBakery-section-heading-main page-heading">MAIN SERVICES WE PROVIDE</h3>
        <p class="feellioBakery-section-heading-sub">discount every Monday</p>
    </div>
    <div class="container">
        <div class="feellioBakeryBannerFour">
            <div class="feellioBakeryBannerFour-banner">
                <div class="feellioBakeryBannerFour-img"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-banner-four-01.jpg" alt="feelio-bakery-banner-four-01.jpg" /></a></div>
                <div class="feellioBakeryBannerFour-body wow fadeIn" data-wow-delay="200ms">
                    <h3 class="feellioBakeryBannerFour-title">SALE BAKERY</h3>
                    <p class="feellioBakeryBannerFour-desc">Generally speaking, the wetter your dough the bigger the holes will be.</p>
                </div>
            </div>
            <div class="feellioBakeryBannerFour-banner">
                <div class="feellioBakeryBannerFour-img"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-banner-four-02.jpg" alt="feelio-bakery-banner-four-02.jpg" /></a></div>
                <div class="feellioBakeryBannerFour-body wow fadeIn" data-wow-delay="200ms">
                    <h3 class="feellioBakeryBannerFour-title">WEDDING CAKE</h3>
                    <p class="feellioBakeryBannerFour-desc">Many people want to know how to make their bread more sour. </p>
                </div>
            </div>
            <div class="feellioBakeryBannerFour-banner">
                <div class="feellioBakeryBannerFour-img"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-banner-four-03.jpg" alt="feelio-bakery-banner-four-03.jpg" /></a></div>
                <div class="feellioBakeryBannerFour-body wow fadeIn" data-wow-delay="200ms">
                    <h3 class="feellioBakeryBannerFour-title">PROVIDE MATERIALS</h3>
                    <p class="feellioBakeryBannerFour-desc">I keep mine pretty thick. It has to be spooned out of the jar.</p>
                </div>
            </div>
            <div class="feellioBakeryBannerFour-banner">
                    <div class="feellioBakeryBannerFour-img"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-banner-four-04.jpg" alt="feelio-bakery-banner-four-04.jpg" /></a></div>
                    <div class="feellioBakeryBannerFour-body wow fadeIn" data-wow-delay="200ms">
                        <h3 class="feellioBakeryBannerFour-title">TRAINING BAKER</h3>
                        <p class="feellioBakeryBannerFour-desc">Some starters are very liquidy and can be poured out of their containers.</p>
                    </div>
                </div>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Bakery Banner One

![homepage-section](img/section-bakery-banner-one.png)

---

* **HTML Content:**

```html
{{#block "feellio-bakery-banner-one"}}
<div class="chiara-section feellio-section--bakeryBannerOne">
    <div class="feellioBakeryBannerOne">
        <div class="feellioBakeryBannerOne-banner">
            <div class="feellioBakeryBannerOne-img"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-banner-one-01.jpg" alt="feelio-bakery-banner-one-01.jpg" /></a></div>
            <div class="feellioBakeryBannerOne-img"><a href="#"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-banner-one-02.jpg" alt="feelio-bakery-banner-one-02.jpg" /></a></div>
            <a href="#" class="feellioBakeryBannerOne-action">Make order now</a>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Bakery Awesome Products

![homepage-section](img/section-bakery-awesome-products.png)

---

* **HTML Content:**

```html
{{#block "feellio-bakery-awesome-products"}}
<div class="chiara-section feellio-section--bakeryAwesome-Products">
    <div class="container">
        <div class="feellioBakeryAwesomeProducts" data-products-by-category-sorting-tabs>
            <div class="feellioBakery-section-heading wow fadeIn">
                <h3 class="feellioBakery-section-heading-main page-heading">AWESOME OUR PRODUCTS</h3>
            </div>
            <ul class="tabs" data-tab>
                <li class="tab is-active">
                    <a class="tab-title" href="#tab-productsByCategory-new-{{index}}">New arrival</a>
                </li>
                <li class="tab">
                    <a class="tab-title" href="#tab-productsByCategory-top-{{index}}">Best seller</a>
                </li>
                <li class="tab">
                    <a class="tab-title" href="#tab-productsByCategory-featured-{{index}}">Featured</a>
                </li>
                <li class="tab">
                    <a class="tab-title" href="#tab-productsByCategory-rating-{{index}}">Top Reviewed</a>
                </li>
            </ul>
            <div class="tabs-contents">
                <div class="tab-content is-active" id="tab-productsByCategory-new-{{index}}" data-url="{{url}}?sort=newest&amp;limit={{limit}}">
                    <img class="img-loading" src="{{cdn 'img/loading.svg'}}" alt="loading" />
                </div>
                <div class="tab-content" id="tab-productsByCategory-top-{{index}}" data-url="{{url}}?sort=bestselling&amp;limit={{limit}}">
                    <img class="img-loading" src="{{cdn 'img/loading.svg'}}" alt="loading" />
                </div>
                <div class="tab-content" id="tab-productsByCategory-featured-{{index}}" data-url="{{url}}?sort=featured&amp;limit={{limit}}">
                    <img class="img-loading" src="{{cdn 'img/loading.svg'}}" alt="loading" />
                </div>
                <div class="tab-content" id="tab-productsByCategory-rating-{{index}}" data-url="{{url}}?sort=avgcustomerreview&amp;limit={{limit}}">
                    <img class="img-loading" src="{{cdn 'img/loading.svg'}}" alt="loading" />
                </div>
            </div>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Bakery Special Boxes

![homepage-section](img/section-bakery-special-boxes.png)

---

* **HTML Content:**

```html
{{#block "feellio-bakery-special-boxes"}}
<div class="chiara-section feellio-section--bakerySpecialBoxes">
    <div class="feellioBakery-section-heading wow fadeIn">
        <div class="feellioBakery-section-heading-img"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/feelio-bakery-special-boxes-heading.jpg" alt="feelio-bakery-special-boxes-heading.jpg" /></div>
        <h3 class="feellioBakery-section-heading-main page-heading">Special boxes</h3>
        <p class="feellioBakery-section-heading-sub">Selection boxes you want</p>
        <p class="feellioBakery-section-heading-desc">Our original contribution to the no-knead bread revolution: substitute live sourdough starter for instant yeast to create the ultimate no knead artisan bread loaf.</p>
    </div>
    <div class="container">
        <ul class="feellioBakerySpecialBoxes" data-slick='{
            "dots": true,
            "arrows": false,
            "mobileFirst": true,
            "slidesToShow": 1,
            "slidesToScroll": 1,
            "autoplay": true,
            "autoplaySpeed": 3000000,
            "responsive": [
                {
                    "breakpoint": 800,
                    "settings": {
                        "vertical": true,
                        "infinite": false
                    }
                }
            ]
        }'>
            <li class="feellioBakerySpecialBoxes-item">
                <div class="feellioBakerySpecialBoxes-product">
                    <div class="feellioBakerySpecialBoxes-product-img">
                        <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/section-bakery-special-boxes-01.jpg" alt="section-bakery-special-boxes-01.jpg" />
                    </div>
                    <div class="feellioBakerySpecialBoxes-product-content">
                        <div class="feellioBakerySpecialBoxes-product-subTitle">Breads combo</div>
                        <h4 class="feellioBakerySpecialBoxes-product-Title">Box of 05 Monthly <br>special</h4> 
                        <div class="feellioBakerySpecialBoxes-product-price">
                            <span class="feellioBakerySpecialBoxes-product-price-sale">$37.00</span>
                            <span class="feellioBakerySpecialBoxes-product-price-main">$29.00</span>
                        </div>
                        <ul class="feellioBakerySpecialBoxes-product-desc">
                            <li>As with any bread recipe, baguette variations abound.</li>
                            <li>Baguettes are an interesting bread.</li>
                        </ul>
                        <dl class="feellioBakerySpecialBoxes-product-info">
                            <dt>categories:</dt>
                            <dd>Vegetable/ Package</dd>
                            <dt>Weight:</dt>
                            <dd>5.8kg / package</dd>
                            <dt>Expire date:</dt>
                            <dd>01/11/2018</dd>
                        </dl>
                        <a href="#" class="feellioBakerySpecialBoxes-product-action">Add to cart</a>
                    </div>
                </div>
            </li>
            <li class="feellioBakerySpecialBoxes-item">
                <div class="feellioBakerySpecialBoxes-product">
                    <div class="feellioBakerySpecialBoxes-product-img">
                        <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/section-bakery-special-boxes-01.jpg" alt="section-bakery-special-boxes-01.jpg" />
                    </div>
                    <div class="feellioBakerySpecialBoxes-product-content">
                        <div class="feellioBakerySpecialBoxes-product-subTitle">Breads combo</div>
                        <h4 class="feellioBakerySpecialBoxes-product-Title">Box of 05 Monthly <br>special</h4> 
                        <div class="feellioBakerySpecialBoxes-product-price">
                            <span class="feellioBakerySpecialBoxes-product-price-sale">$37.00</span>
                            <span class="feellioBakerySpecialBoxes-product-price-main">$29.00</span>
                        </div>
                        <ul class="feellioBakerySpecialBoxes-product-desc">
                            <li>As with any bread recipe, baguette variations abound.</li>
                            <li>Baguettes are an interesting bread.</li>
                        </ul>
                        <dl class="feellioBakerySpecialBoxes-product-info">
                            <dt>categories:</dt>
                            <dd>Vegetable/ Package</dd>
                            <dt>Weight:</dt>
                            <dd>5.8kg / package</dd>
                            <dt>Expire date:</dt>
                            <dd>01/11/2018</dd>
                        </dl>
                        <a href="#" class="feellioBakerySpecialBoxes-product-action">Add to cart</a>
                    </div>
                </div>
            </li>
            <li class="feellioBakerySpecialBoxes-item">
                <div class="feellioBakerySpecialBoxes-product">
                    <div class="feellioBakerySpecialBoxes-product-img">
                        <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/section-bakery-special-boxes-01.jpg" alt="section-bakery-special-boxes-01.jpg" />
                    </div>
                    <div class="feellioBakerySpecialBoxes-product-content">
                        <div class="feellioBakerySpecialBoxes-product-subTitle">Breads combo</div>
                        <h4 class="feellioBakerySpecialBoxes-product-Title">Box of 05 Monthly <br>special</h4> 
                        <div class="feellioBakerySpecialBoxes-product-price">
                            <span class="feellioBakerySpecialBoxes-product-price-sale">$37.00</span>
                            <span class="feellioBakerySpecialBoxes-product-price-main">$29.00</span>
                        </div>
                        <ul class="feellioBakerySpecialBoxes-product-desc">
                            <li>As with any bread recipe, baguette variations abound.</li>
                            <li>Baguettes are an interesting bread.</li>
                        </ul>
                        <dl class="feellioBakerySpecialBoxes-product-info">
                            <dt>categories:</dt>
                            <dd>Vegetable/ Package</dd>
                            <dt>Weight:</dt>
                            <dd>5.8kg / package</dd>
                            <dt>Expire date:</dt>
                            <dd>01/11/2018</dd>
                        </dl>
                        <a href="#" class="feellioBakerySpecialBoxes-product-action">Add to cart</a>
                    </div>
                </div>
            </li>
        </ul>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Bakery Instagram

![homepage-section](img/section-bakery-instagram.png)

---

* **HTML Content:**

```html
{{#block "feellio-bakery-instagram"}}
<div class="chiara-section feellio-section--bakeryInstagram">
    <div class="container">
        <div class="feellioBakeryInstagram">
            <div class="feellioBakery-section-heading">
                    <div class="feellioBakery-section-heading-bg">
                        <img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/section-bakery-instagram-bg.jpg" alt="section-bakery-instagram-bg.jpg" />
                    </div>
                    <div class="feellioBakery-section-heading-img"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/section-bakery-instagram-heading.png" alt="section-bakery-instagram-heading.png" /></div>
                    <h3 class="feellioBakery-section-heading-main page-heading">our gallery</h3>
                    <p class="feellioBakery-section-heading-sub">made for you with love</p>
                    <p class="feellioBakery-section-heading-desc">Our Boiceville location is our original home and our wood-fired brick oven craft bakery.  We offer breakfast, lunch, and brunch 7 days per week. Come visit us.</p>
                    <div class="feellioBakery-section-heading-action">
                        <i class="icon"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg></i>
                        <div class="feellioBakery-section-heading-action-text">
                            <p>Follow us on instagram</p> 
                            <span>@</span><a href="#">breadpro_store</a>
                        </div>
                    </div>
                </div>
            <div class="feellioBakeryInstagram-content">
                <!-- <div id="instafeed" data-accessToken="10094437813.1677ed0.f843f6b3588944b794bb6e2deafb00ee" data-limit="12"></div> -->
                <div id="instafeed">
                        <div class="feellio-bakery-instafeed-item"><a href="#" target="_blank"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/fellio-bakery-instagram-01.jpg" alt="fellio-bakery-instagram-01.jpg" /></a></div>
                        <div class="feellio-bakery-instafeed-item"><a href="#" target="_blank"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/fellio-bakery-instagram-03.jpg" alt="fellio-bakery-instagram-03.jpg" /></a></div>
                        <div class="feellio-bakery-instafeed-item g-r-e-2"><a href="#" target="_blank"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/fellio-bakery-instagram-06.jpg" alt="fellio-bakery-instagram-06.jpg" /></a></div>
                        <div class="feellio-bakery-instafeed-item"><a href="#" target="_blank"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/fellio-bakery-instagram-07.jpg" alt="fellio-bakery-instagram-07.jpg" /></a></div>
                        <div class="feellio-bakery-instafeed-item g-r-e-2"><a href="#" target="_blank"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/fellio-bakery-instagram-02.jpg" alt="fellio-bakery-instagram-02.jpg" /></a></div>
                        <div class="feellio-bakery-instafeed-item"><a href="#" target="_blank"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/fellio-bakery-instagram-04.jpg" alt="fellio-bakery-instagram-04.jpg" /></a></div>
                        <div class="feellio-bakery-instafeed-item g-r-e-2"><a href="#" target="_blank"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/fellio-bakery-instagram-08.jpg" alt="fellio-bakery-instagram-08.jpg" /></a></div>
                        <div class="feellio-bakery-instafeed-item g-c-e-2"><a href="#" target="_blank"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/fellio-bakery-instagram-05.jpg" alt="fellio-bakery-instagram-05.jpg" /></a></div>
                </div>
            </div>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## --- Section Bakery Blog

![homepage-section](img/section-bakery-blog.png)

---

* **HTML Content:**

```html
{{#block "feellio-bakery-blog"}}
<div class="chiara-section feellio-section--bakeryBlog">
    <div class="feellioBakeryBlog">
        <div class="feellioBakery-section-heading wow fadeIn">
            <div class="feellioBakery-section-heading-img"><img class="lazyload" src="{{cdn 'assets/img/loading.svg'}}" data-src="/product_images/uploaded_images/section-bakery-blog-heading.jpg" alt="section-bakery-blog-heading.jpg" /></div>
            <h3 class="feellioBakery-section-heading-main page-heading">Blog update</h3>
            <p class="feellioBakery-section-heading-sub">Check our latest blog post</p>
            <p class="feellioBakery-section-heading-desc">Flour &amp; Water is a book project built in the spirit of internet: chapters are published straight to the web site and then edited based on feedback from readers.</p>
        </div>
        <div class="container">
            <div class="feellioBakeryBlog-blog">
                <ul class="feellioBakeryBlog-posts">
                    {{#each blog.recent_posts}}
                        <li class="feellioBakeryBlog-posts-item">
                            <div class="feellioBakeryBlog-posts-image">
                                {{#if thumbnail}}
                                        <a href="{{url}}">
                                            <img class="lazyload" data-sizes="auto" src="{{cdn 'img/loading.svg'}}" data-src="{{#if large_image}}{{getImage thumbnail 'blog_post_size'}}{{else}}{{getImage thumbnail 'blog_size'}}{{/if}}" alt="{{thumbnail.alt}}" title="{{thumbnail.alt}}">
                                        </a>
                                {{/if}}
                            </div>
                            <div class="feellioBakeryBlog-posts-content">
                                <h4 class="feellioBakeryBlog-post-title">{{title}}</h4>
                                <div class="feellioBakeryBlog-post-date">{{date_published}}</div>
                            </div>
                            <div class="feellioBakeryBlog-post-summary">{{{summary}}}</div>
                            <div class="feellioBakeryBlog-post-link">
                                <a class="feellioBakeryBlog-post-action" href="{{url}}">Read more <i class="icon"><svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 476.213 476.213" xml:space="preserve"> <polygon points="345.606,107.5 324.394,128.713 418.787,223.107 0,223.107 0,253.107 418.787,253.107 324.394,347.5 345.606,368.713 476.213,238.106 "/> </svg></i></a>
                            </div>
                        </li>
                    {{/each}}
                </ul>
            </div>
        </div>
    </div>
</div>
{{/block}}
```

---

* You can change content of this section by edit the file `templates/feellio-custom.html`.

![homepage-section](img/how-to-overwrite-a-section-content.png)

---

## IMAGES OR BRANDS CAROUSEL

![homepage brands carousel](img/homepage-brands-carousel.png)

To display the images carousel, create a new banner in **Marketing** > **Banners**:

* **Banner Name**: `Brands carousel (brands-carousel)`
* **Banner Content**: Click on the HTML to edit HTML source.

```html
<ul class="chiara-brandsCarousel-slider" data-remote-brand-position="chiara-brand-banner-homepage">
<li class="chiara-brandsCarousel-item"><a title="Brand 1" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand1.jpg" alt="Brand 1" /> </a></li>
<li class="chiara-brandsCarousel-item"><a title="Brand 2" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand2.jpg" alt="Brand 2" /> </a></li>
<li class="chiara-brandsCarousel-item"><a title="Brand 3" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand3.jpg" alt="Brand 3" /> </a></li>
<li class="chiara-brandsCarousel-item"><a title="Brand 4" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand4.jpg" alt="Brand 4" /> </a></li>
<li class="chiara-brandsCarousel-item"><a title="Brand 5" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand5.jpg" alt="Brand 5" /> </a></li>
<li class="chiara-brandsCarousel-item"><a title="Brand 6" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand6.jpg" alt="Brand 6" /> </a></li>
<li class="chiara-brandsCarousel-item"><a title="Brand 7" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand7.jpg" alt="Brand 7" /> </a></li>
<li class="chiara-brandsCarousel-item"><a title="Brand 8" href="#"> <img src="https://cdn8.bigcommerce.com/s-o0llnqp9lx/product_images/uploaded_images/brand8.jpg" alt="Brand 8" /> </a></li>
</ul>
```

Or use button below to generate HTML code with your custom content:

<!-- Button trigger modal -->
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#chiara_home_banner3_modal">
  Launch Banner Code Generator
</button>

* **Show on Page**: `Home Page`
* **Location**: `Top of Page`