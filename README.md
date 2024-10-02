<a id="readme-top"></a>

<div align="center">
  <h2 align="center">Cybersecurity & Rust Hackathon</h3>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about">About</a>
      <ul>
        <li><a href="#learning-goals">Learning Goals</a></li>
      </ul>
    </li>
    <li>
      <a href="#first-project">First Project</a>
    </li>
    <li>
      <a href="#second-project">Second Project</a>
      <ul>
        <li><a href="#rust-learning">Rust Learning Takeaways</a></li>
      </ul>
    </li>
    <li>
      <a href="#third-project">Third and Final Project</a>
    </li>
    <li>
      <a href="#conclusions">Conclusions</a>
    </li>
  </ol>
</details>



<!-- ABOUT -->
## About

A specific job posting sparked and interest in me to learn more about cybersecurity related to networks, that lead me to deep dive into network protocols, TLS and cryptography. Then I figured that since I'm very much a learn-by-doing sort of fellow, why not build some small projects around those topics.

I decided to put these days I have before the application period ends into good use and create a personal 10-day hackathon for myself.
The posting also wished for Rust knowledge, and I realized that maybe instead of just saying I could learn it quickly, why wouldn't I just show it. So I added coding in rust into the mix here.

### Learning Goals
- How networks are secured?
  - How hashing and cryptography relate to it?
  - How exactly on a functional level do HTTP and TLS combine to make HTTPS?
- Get to a level where I can semi-comfortably code with Rust
- Get a better at handling bits

<!-- FIRST PROJECT -->
## First Project: [ping](https://github.com/Rubidium7/ping) <a id="first-project"></a>

To kick things off I started with this simple network protocol related exercise. I wanted to keep it small so I could leave more time for the bigger and rustier fish. 
This I made in C as translating and learning about all the needed syscalls to Rust seemed like it would eat up way too much of my time for this. It was also nice to start out on a bit more of a familiar ground.
I'm already quite familiar with low-level network and socket programming from when made my own [irc server](https://github.com/Rubidium7/ft_irc), but I learned more about ip addresses, domains and managing sending and receving packets here.

<!-- SECOND PROJECT -->
## Second Project: [md5](https://github.com/Rubidium7/md5) <a id="second-project"></a>

Here we get to Rust, how exciting. I've found that the best way I learn a new coding language (or actually most things) is by just jumping right to it.
I did read some bit of [The Rust Programming Language Book](https://doc.rust-lang.org/book/ch00-00-introduction.html) to get started, but after that I just started writing and learning on the fly.

For this I also did a lot of reading about cryptography/hashing and how it's applied in modern networking. 
Funnily enough the hardest part wasn't writing the algorithm itself, but figuring out how to manage things on a bit level with the padding etc.

### Some of my takeaway points from the Rust learning process <a id="rust-learning"></a>
- the rust compiler's attitude did take a bit to get used to, but in the end I do really appreciate the fact that after getting the program to compile you can really trust that it won't suddenly crash and burn (looking at you gcc)
- a lot of the rust methods felt really natural coming from c++ and python (yes, i really didn't expect either it would have so many similarities with python)
- the most difficult part about this project ended up being trying to define an error type and also simutaniously using predefined error types. I didn't expect it would ~~be so hard~~ lead to such a fruitful road of learning about intergral rust concepts such as closures, boxes, results etc.
- it did make me think about the less talked about potential vulnerabilities of languages like C, for example accepting numbers to overflow and having a NULL-type

<!-- THIRD PROJECT -->
## Third and Final Project: [sha256](https://github.com/Rubidium7/sha256) <a id="third-project"></a>

It was really nice to see how much more comfortable writing this in rust already was. This time it didn't take me and hour plus to get the dang thing to compile. 
This wasn't anyway as hard to write anymore after the md5 as they share a lot of features.
Though I'm happy to have an actual secure cryptographical algorithm in my library, maybe I could utilize this in a future coding an https server from scratch project 🤔😉

<!-- CONCLUSIONS -->
## Conclusions
Tbh I'm really proud of myself for getting here and completing all of my goals for this hackathon. Can't say it wasn't intense doing this while juggling my part-time jobs, but really the interest in the topics kept me going.

And I'm happy to have thrown myself into the deep end with Rust here, I think this'll be a beginning of something beautiful no matter if I get the job or not. I did find myself really enjoying writing it, and I seriously do appreciate and respect the safeness.

All in all a fun challenge, I'm glad to have found so many new interesting topics to continue exploring. Peace 🦕✌

<p align="right">(<a href="#readme-top">back to top</a>)</p>
