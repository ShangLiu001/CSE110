
# Hi I am Shang
## And here's everything I want you to know 
### About my past projects (resume) 

*Nice to meet you!*

![Here's a picture of me at the TV station as a guest.](https://idyllic-moxie-4e6cf1.netlify.app/Radiostation.webp)

***Appstore: An Interactive App Purchase Platform***
Frontend: Designed a full-stack application for software purchase using React JS. Implemented features for users to upload, search, and browse all kinds of software uploaded. Token-based user authorization was used for registration/login/logout purposes.
Backend: Launched a microservice in Go to handle register/login/logout/upload/checkout requests. The backend was deployed on Google App Engine. Elasticsearch was used to provide the search function for users and was deployed to Google Compute Engine. Also, Stripe APIs were used to handle user transactions and checking out.

***Mobile news: An Instagram -like News App***
Designed an Instagram alike News App based on the Google Component Architectural MVVM pattern.
Implemented the bottom bar & page navigation using the JetPack navigation component.
Utilized 3rd party CardStackView (Recycler View) to support swipe gestures for liking/disliking the news.
Built the Room Database with LiveData & ViewModel to support a local cache and offline model.
Integrated Retrofit and LiveData to pull the latest news data from a RESTful endpoint (newsapi.org).

***NFT Price Visualization***
Built an NFT dashboard that enables searching, viewing, and analyzing NFT assets. NFT relevance like name, description, logo, and prices was obtained from calling Moralis public APIs and then processed using React JS. Historical price was visualized using recharts, and Ant design UI was used for succinctness and clearness.

**My favorite quote is from President Joe Biden (just for fun)**
>"America is a nation that can be defined in a single word : Asufutimaehaehfutbw..."


**Some clips of short code I just randomly grabbed somewhere about BFS:**
```
public static ArrayList<Integer>
bfsOfGraph(int V, ArrayList<boolean> adj[])
{
    ArrayList<Boolean> vis = new ArrayList<>(V);
    ArrayList<Integer> bfs_traversal = new ArrayList<>();
    for (int i = 0; i < V; ++i) {
        // To check if already visited
        if (vis.get(i) == false) {
            Queue<Integer> q = new LinkedList<>();
            vis.set(i, true);
            q.add(i);
 
            // BFS starting from ith node
            while (!q.isEmpty()) {
                int g_node = q.peek();
                q.poll();
                bfs_traversal.add(g_node);
                for (int it = 0;
                     it < adj[g_node].toArray().length;
                     it++) {
                    if (adj[g_node].get(it) == true) {
                        if (vis.get(it) == false) {
                            vis.set(it, true);
                            q.add(it);
                        }
                    }
                }
            }
        }
    }
    return bfs_traversal;
}
```


**You will be directed to [My website created in CSE134B](https://idyllic-moxie-4e6cf1.netlify.app/).**

**This is a section link [link to the top of the page](#hi-i-am-shang).**

**Link to other files: [link to another .md file](./anotherfiletobedirected.md).**

#### Unordered List of languages and skills I learnt

* Java
* Python
* Go
* JavaScript
* HTML&CSS
* C++
* C
* SQLite
* MySQL
* Spring Boot
* React
  

#### What will I do when I am free

1. GET SOME SLEEP!
2. Play boardgames with friends
3. Kayaking & enjoy the beach


### Task lists of the courses I am doing these quarters

- [ ] CSE 141
- [ ] CSE 141L
- [ ] CSE 110
- [ ] CSE 101
- [ ] CSE 150B
- [x] CSE 134B (just done)
