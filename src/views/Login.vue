<template>
  <main role="main" class="container">
    <div class="row justify-content-center">
      <aside class="col-sm-6 align-self-center">
        <div class="card">
          <article class="card-body">
            <a href class="float-right btn btn-outline-primary">Sign up</a>
            <h4 class="card-title mb-4 mt-1">Sign in</h4>
            <form>
              <div class="form-group">
                <label>Your email</label>
                <input name class="form-control" placeholder="Email" type="email" />
                <p class="text-danger mt-1">Error message</p>
              </div>
              <!-- form-group// -->
              <div class="form-group">
                <a class="float-right" href="#">Forgot?</a>
                <label>Your password</label>
                <input class="form-control" placeholder="******" type="password" />
              </div>
              <!-- form-group// -->
              <div class="form-group">
                <div class="checkbox">
                  <label>
                    <input type="checkbox" /> Save password
                  </label>
                </div>
                <!-- checkbox .// -->
              </div>
              <!-- form-group// -->
              <div class="form-group">
                <button type="submit" class="btn btn-primary btn-block">Login</button>
              </div>
              <!-- form-group// -->
            </form>
          </article>
        </div>
        <!-- card.// -->
      </aside>
      <!-- col.// -->
    </div>
  </main>
</template>

<script>
export default {
  name: 'login',
};
</script>
