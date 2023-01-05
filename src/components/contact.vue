<template>
    <div class="contact">
        <h1>{{ title }}</h1>
        <form action="">
          <fieldset>
            <legend>Contact us</legend>
            <div class="form-group row">
              <label for="staticEmail" class="col-sm-2 col-form-label">Name</label>
            <div class="col-sm-10">
              <input type="text" readonly="" class="form-control-plaintext" id="staticEmail" value="Ramesh" placeholder="Enter your name">
            </div>
            <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
          <div class="col-sm-10">
            <input type="text" readonly="" class="form-control-plaintext" id="staticEmail" value="email@example.com">
          </div>
            <label for="exampleInputPassword1" class="form-label">Password</label>
            <input type="password" class="form-control-plaintext" id="exampleInputPassword1" placeholder="Password"> <br> <br>
          <button type="submit" class="btn btn-primary">Submit</button>
          </div>
          </fieldset>
        </form>
    </div>
</template>

<script>
export default {
  name: 'contact',
  data () {
    return {
      title: 'Welcome to Your Contact Page'
    }
  }
}

</script>
