{
  session {
    currentUser: {
      id: 10,
      username: "billy",
      name: "billy joe bob",
      liked_posts: [],
      following: [],
      followers: 9999
    },
    userProfile: {
      id: 99,
      username: "jim",
      name: "jim bob joe",
      following: [],
      followers: []
    },
    posts: {
      1: {
        id: 1,
        description: "sick pic",
        img_url: "pic.com",
        poster: {
          poster_id: 12,
          poster_username
        }
        likes: 111,
        comments: {
          1: {id: 1, poster_id: 12, poster_username: 'jim', body: 'where?'},
          2: {....}
        }
      }
    },
    searchResult: [{username: "billy", id: 10}],
    errors: {
      signUp: [],
      login: [],
      createPost: []
    }
  }
}
