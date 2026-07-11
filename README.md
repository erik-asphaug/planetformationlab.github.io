# planetformationlab.github.io
# Planet Formation Lab Website Manager

Welcome to the lab repository! This repository hosts our public website at [planetformationlab.org](https://planetformationlab.org). 

Any modifications committed directly to the `main` branch will automatically build and update the live website within seconds.

---

## 📝 How to Update Content

You do not need any coding software to update your papers or press mentions. You can do it directly on Github.com.

### Adding a Recent Paper
1. Open the `index.html` file above.
2. Click the **Pencil Icon** (Edit this file) in the top-right corner.
3. Scroll down until you find the `Recent Papers` section (around line 140). It looks like this:
   ```html
   <!-- Publications Directory -->
   <section>
       <h2>Recent Papers</h2>
       <ul>
           <li>
               <a href="YOUR_LINK_HERE" class="item-link">YOUR PAPER TITLE HERE</a>
               <span class="meta">Journal Name (Year)</span>
           </li>
       </ul>
   </section>
   ```
4. Copy an existing `<li> ... </li>` block, paste it directly beneath, and update it with your paper's URL, title, and journal metadata.
5. Scroll to the bottom of the screen, click the green **Commit changes...** button, and save.

### Adding a News or Media Story
1. Open the `index.html` file.
2. Click the **Pencil Icon** to edit.
3. Find the `Lab News & Media Coverage` section (around line 125). It looks like this:
   ```html
   <div class="news-item">
       <span class="news-tag">Media Source Name</span>
       <h3><a href="YOUR_LINK" class="item-link" target="_blank">STORY HEADLINE</a></h3>
       <p class="meta">Date — Brief snippet description or quote details.</p>
   </div>
   ```
4. Copy a `<div class="news-item"> ... </div>` block, paste it right below, and fill in the details.
5. Click **Commit changes...** at the bottom to publish.

---

## 🔒 Security & Guidelines
* **Meeting Links**: Do not change the `YOUR_MEETING_ID` parameters unless the lab links have officially migrated. Keep passwords out of the public code description.
* **Review Changes**: Double-check your HTML tags (`<li>`, `<a>`, `</div>`). Leaving a tag unclosed can break the layout styling of the homepage.
