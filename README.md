# OctoNuts
## Description.
The html and CSS presented to me displayed an apealing website but the code istelf was not efficient and could create problems in future iterations.  There were also no alt tags for any of the images and the links in the header were broke. 

For this project I began by looking at the html and replaced all or most of the <div> with more appropriate semantics. I took the first <div> and turned it into the <header> (classifying a <div> as a <header> is verbose). I removed the next <div> and replaced it with <nav>. I also thought it was a bit cleaner to remove the <ul> and simply listed the <a> elements as such within the <nav> element. These changes took care of the <header>. 

So I moved on to the next part of the <body>. Here I I took the hero <div> and turned it into a <figure> which seemd to be logical and would keep it semantically separate from the next section. 

After the <figure> I changed the next set of <div>s into the <main> with three <section>s. Each of the sections recieved an <id>.
