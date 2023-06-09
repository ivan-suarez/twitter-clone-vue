

<template id="template">
  <div id="tmp">
    <div id="left">
      <div id="nav-bar">
        <div id="logo"></div>
        <div>Home</div>
        <div>Explore</div>
        <div>Notifications</div>
        <div>Messages</div>
        <div>Lists</div>
        <div>Bookmarks</div>
        <div>Verified</div>
        <div>Profile</div>
        <div>Options</div>
        <button>Tweet</button>
      
    </div>
  <div id="profile-menu">
        <div id="profile-picture"></div>
        <div>Elon Musk</div>
        <div>@elonmusk</div>
      </div>
    </div>
    
  <div id="content">
    <div>Home</div>
    <div>What is happening?!
      <button>Tweet</button>
    </div>
    <div id="tweet">
      <div>SpaceX</div>
      <div>Liftoff!</div>
      <div id="media"></div>
    </div>
  </div>
  <div id="ads">
    <div>Search Twitter</div>
    <div>What's happening</div>
    <div>Who to follow</div>
  </div>
  </div>
  
  
</template>

<style>
#tmp{
  display: flex;
}

#content{
  border-style: solid;
  border-color: lightgray;
  flex: 1;
  min-height: 100vh;
}

#tweet{
  border-style: solid;
  border-color: lightgray;
}

#left{
  display: flex;
  flex: 1;
  min-height: 100vh;
  justify-content: space-between;
  flex-direction: column;
  align-items: flex-end;
}

#nav-bar{
  display: flex;
  flex-direction: column;
  
}

#ads{
  flex: 1;
}
#profile-menu{
  justify-content: flex-end;
}

</style>
