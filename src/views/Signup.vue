<template>
    <div class="signup">
      <h1>Registracija</h1>
      <div class="container">
        <div class="row">
          <div class="col-sm"></div>
          <div class="col-sm">
            <form>
              <div class="form-group">
                <label for="email">Email adresa</label>
                <input type="email" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Unesite email" />
                <small id="emailHelp" class="form-text text-muted">Nikada nećemo dijeliti vašu email adresu s drugima.</small>
              </div>
              <div class="form-group">
                <label for="password">Lozinka</label>
                <input type="password" class="form-control" id="password" placeholder="Lozinka" />
              </div>
              <div class="form-group">
                <label for="confirmPassword">Potvrdi lozinku</label>
                <input type="password" class="form-control" id="confirmPassword" placeholder="Potvrdi lozinku" />
              </div>
              <button type="submit" class="btn btn-primary">Registriraj se</button>
            </form>
          </div>
          <div class="col-sm"></div>
        </div>
      </div>
    </div>
  </template>
  
   