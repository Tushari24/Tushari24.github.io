
<template>
  <div ui-view class="app-body" id="view">
    <div class="padding">
      <div class="row">
        <!-- first col -->
        <div class="col-xs-6 col-md-4">
          <div class="box">
            <div class="box-tool"></div>
            <div class="p-a-md text-center">
              <p>
                <img src="../../assets/images/pp.jpg" class="img-circle w-xs" />
              </p>
              <a href class="text-md block">Tushar Ighawe</a>
              <p>
                <small>Pune, India</small>
              </p>
              <div>
                <a target="_blank" href="https://www.facebook.com/Tushar.ighawe1848" class="btn btn-icon btn-social rounded white btn-sm">
                  <i class="fa fa-facebook"></i>
                  <i class="fa fa-facebook indigo"></i>
                </a>
                <a target="_blank" href="https://www.instagram.com/tushar_i25/" class="btn btn-icon btn-social rounded white btn-sm">
                  <i class="fa fa-instagram"></i>
                  <i class="fa fa-instagram light-blue"></i>
                </a>
                <a href="mailto:tusharighawe@gmail.com" target="_top" class="btn btn-icon btn-social rounded white btn-sm">
                  <i class="fa fa-google"></i>
                  <i class="fa fa-google red"></i>
                </a>
              </div>
              <div class="text-center m-t">
                <a target="_blank" href="https://www.instagram.com/tushar_i25/" class="btn btn-sm rounded primary w-sm m-y-xs">Follow</a>
              </div>
            </div>
            <div class="p-a">
              <a href class="text-ellipsis">
                <i class="fa fa-globe text-muted m-r-sm"></i> dropitlikehotspot.com
              </a>
            </div>
          </div>
        </div>

        <!-- middle col -->
        <div class="col-xs-12 col-sm-6 col-md-8">
          <div class="box">
            <div class="box-header">
              <h3>
                Feeds Here &nbsp;
                <span class="label success">2</span>
              </h3>
            </div>
            <div class="box-body"></div>
            <div class="box-color info pos-rlt">
            <span class="arrow left b-info"></span>
            <div class="box-body">
              {{msg}}
            </div>
          </div>


            <div class="box-color warning pos-rlt">
              <span class="arrow left b-warning"></span>
              <div class="box-body">{{msgTwo}}</div>
            </div>
            
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "view",
  data() {
    return {
      msg: "Welcome to Your dropit Blog",
      msgTwo: "Site under Construction"
    };
  }
};
</script>

<style scoped>
</style>
