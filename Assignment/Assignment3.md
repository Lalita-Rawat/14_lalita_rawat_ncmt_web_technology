# CHAPTER 3: WEBSITE STRUCTURE DESIGN
## Group A: Short Questions (2 Marks)

### 1. Define Information Architecture (IA).
**Ans:** 
Information Architecture (IA) is the process of organizing, structuring, and labeling content on a website so users can easily find what they need.
It helps improve usability and navigation by arranging information in a clear and logical way.

### 2. What is a “Wireframe”?
**Ans:** 
A wireframe is a basic visual blueprint of a website that shows layout, structure, and placement of elements like menus and buttons.
It focuses on functionality and layout, not colors, images, or final design.

### 3. Explain the concept of “Cognitive Friction” in web design.
**Ans:**
Cognitive friction occurs when a website forces users to think too much to complete a task.
Poor navigation, confusing layouts, or unclear labels increase cognitive friction and reduce user satisfaction.

### 4. Why should URL slugs use hyphens instead of underscores?
**Ans:**
Search engines treat hyphens as word separators, but underscores join words together.
For example, web-design is easier to read and better for SEO than web_design.

## Group B: Long Questions (4 Marks)

### 5. Compare and contrast Hierarchical (Tree) structure and Linear (Sequential) structure. Give examples.
**Ans:** 
A Hierarchical (Tree) structure organizes content in a top-down manner, starting from a homepage and branching into categories and subcategories.
It is commonly used for large websites where content needs clear classification.

*Advantages:*

Easy to navigate

Scalable for large websites

Users can quickly locate information

Example:
A university website where the homepage leads to Admissions, Departments, and Student Services, and each has sub-pages.

A Linear (Sequential) structure presents information in a fixed step-by-step order. Users must follow a specific sequence without skipping steps.

*Advantages:*

Simple and guided flow

Good for learning or instructions

Example:
An online course or checkout process where users move from Step 1 → Step 2 → Step 3.

**Comparison Summary:**
Hierarchical structure offers flexibility and choice, while linear structure controls the user journey. The choice depends on website size and purpose.

### 6. Explain the “Three-Click Rule” and its significance in UX design.
**Ans:**
The Three-Click Rule states that a user should be able to find any information on a website within three clicks.
If it takes more than three clicks, users may feel frustrated and leave the site.

This rule highlights the importance of clear navigation and logical structure.
While not a strict rule, it encourages designers to reduce unnecessary steps and simplify user journeys.

**Significance in UX Design:**

Improves user satisfaction: When users can find information quickly and easily, they feel comfortable using the website. Clear navigation and fewer clicks reduce frustration, which makes users happy and encourages them to stay longer on the site

Reduces bounce rate:Bounce rate refers to users leaving a website after viewing only one page. If navigation is simple and information is easy to access, users are more likely to explore multiple pages instead of leaving immediately.

Makes content easier to discover:A well-structured website helps users understand where information is located. Logical menus, clear labels, and fewer clicks make it easier for users to discover important content without confusion. 

A well-designed website may sometimes take more than three clicks, but as long as navigation is clear, users remain comfortable.

### 7. “Plan before you do.” Explain how Card Sorting and Flowcharts help in planning a website’s structure.
**Ans:**
Planning is essential before designing a website to avoid confusion later. Card Sorting and Flowcharts are important tools used during the planning stage.

Card Sorting helps designers understand how users group information naturally.
Users organize content cards into categories, helping designers create a structure that matches user expectations.

Flowcharts visually map the user journey from one page to another.
They show how users move through pages, helping identify missing links or unnecessary steps.

Together, these tools ensure:

Better navigation

User-friendly structure

Reduced redesign effort

Thus, planning tools help create efficient and logical website structures.

# Group C: Scenario-Based Questions (5 Marks)
### 8. You are designing a website for a University. It has hundreds of pages (Admissions, Departments, Alumni, News). Which structural model would you choose? Draw a rough diagram and justify your choice.
**Ans:** 
For a University website with hundreds of pages, the Hierarchical (Tree) structure is the most suitable.

This type of website contains multiple categories such as Admissions, Departments, Alumni, Research, and News. A hierarchical structure helps organize this large amount of content logically.

Rough Diagram:
Home
 ├── Admissions
 │    ├── Undergraduate
 │    ├── Postgraduate
 │    └── Scholarships
 ├── Departments
 │    ├── Science
 │    ├── Arts
 │    └── Engineering
 ├── Alumni
 ├── News & Events
 └── Contact

**Justification:**

Easy navigation for students, staff, and visitors

Scalable as new departments or pages can be added

Clear relationship between pages
Therefore, a hierarchical structure improves usability and content management for a university website.

### 9. A user visits a website but leaves within 10 seconds because they cannot find the navigation menu, which is hidden behind a small icon on a desktop screen. Analyze this design failure using the ”KISS” (Keep It Simple) principle.
**Ans:**
The KISS principle (Keep It Simple, Stupid) states that designs should be simple and easy to understand.

In this case, hiding the navigation menu behind a small icon on a desktop screen violates the KISS principle.
Desktop users expect visible menus, not hidden ones like on mobile devices.

**This design failure causes:**

Confusion

Increased cognitive friction

User frustration

As a result, users leave within seconds because they cannot find basic navigation.

**Better Solution:**

Display a clear, visible navigation bar

Use icons only as secondary elements

Keep essential features obvious

Following KISS ensures better usability and user retention.

### 10. An e-commerce website has a URL structure like www.shop.com/prod?id=55&cat=9. Explainwhy this is bad for both users and Search Engines (SEO), and propose a better structure using Page Slugs.
**Ans:** 
The given dynamic URL (www.shop.com/prod?id=55&cat=9) is problematic for both user experience and search engine optimization.

**Problems:**

*For Users:*

Unreadable and Unfriendly: The URL is a string of parameters (id=55, cat=9) that is meaningless to humans. A user cannot glance at it to understand what page they are on ("Is this a laptop or a shirt?"). This reduces trust and clarity.

Poor Shareability and Recall: Such URLs are hard to remember, read aloud, or share manually. They look technical and potentially suspicious, which can deter sharing via social media or messaging.

No Context in Browser History: When reviewing browser history, all pages just appear as "prod?id=...", making it impossible to distinguish between them.

*For Search Engines (SEO):*

Weak Keyword Relevance: Search engine crawlers derive meaning from URLs. This URL contains no descriptive keywords about the product or category ("laptop," "running-shoes"), missing a key on-page SEO signal.

Crawlability Issues: While search engines can crawl parameter-based URLs, overly complex or duplicate parameter strings can sometimes lead to inefficient crawling or indexing problems.

Lower Click-Through Rate (CTR) in SERPs: In search results, a clear, descriptive URL acts as a minor relevancy signal and is more appealing to users, leading to a higher likelihood of clicks compared to a cryptic, parameter-heavy one.

Proposed Better Structure Using Page Slugs:
A page slug is the descriptive part of a URL that identifies a specific page in a human-readable format. The site should adopt a hierarchical, keyword-rich URL structure with hyphens as word separators.

*Improved URL Examples:*

For a Product Page:
www.shop.com/electronics/laptops/acer-swift-3-2024
(Structure: Category / Sub-category / Product-Name-Slug)

For a Category Page:
www.shop.com/men/footwear/running-shoes

**Benefits of this New Structure:**

User-Friendly: Clearly describes the content. Users and search engines instantly know the page is about the "Acer Swift 3 (2024) Laptop" in the "Electronics > Laptops" section.

SEO Advantage: Includes relevant keywords in the URL path, strengthening topical relevance for search queries.

Improved Navigation: The hierarchical structure mirrors the site's information architecture, aiding user orientation.

Shareable & Trustworthy: Looks clean, professional, and is easy to share or bookmark.

This change transforms URLs from obscure technical commands into valuable, readable pieces of content and navigation aids.
