<template>
    <header class="container">
        <div><img alt="dc logo" src="@/assets/img/dc-logo.png"></div>
        <nav>
          <a href="#">characters</a>
          <a href="#" class="active">comics</a>
          <a href="#">movies</a>
          <a href="#">tv</a>
          <a href="#">games</a>
          <a href="#">collectibles</a>
          <a href="#">videos</a>
          <a href="#">fans</a>
          <a href="#">news</a>
          <a href="#">shop</a>
        </nav>
    </header>
    
</template>

<style lang="scss" scoped>

.container{
    display: flex;
    padding: 1rem;
    justify-content: space-between;
    align-items: center;
}
nav {
      margin: 2rem 0;

      a{
          padding: 3rem 0.5rem;
          text-decoration: none;
          font-size: 0.9rem;
          color: #333;
          font-weight: 600;
          text-transform: uppercase;
          margin-right: 10px;
          height: 100%;
          

          &.active{
              color: #0282f9;
              border-bottom: 3px solid #0282f9;
          }

          
          &:hover{
              color: #0282f9;
              border-bottom: 3px solid #0282f9;
          }
        }
    }
</style>