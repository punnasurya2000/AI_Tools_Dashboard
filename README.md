# AI Tools Dashboard

This project provides a simple dashboard to explore various AI tools, categorized by use case. The dashboard is built with **HTML**, **CSS**, and **JavaScript**. You can browse different categories, such as **Content Generation**, **Image Generation**, and **Conversational AI**, and view relevant tools with short descriptions and external links.

---

## Reason

Many AI tools exist for different use cases, and it can be challenging to keep track of them all. The **AI Tools Dashboard** centralizes these tools into a single, easy-to-navigate interface, providing a quick overview of what each tool does and where to find it.

---

## Features

1. **Dynamic Category Loading**  
   - Click a category link in the sidebar, and the main content area updates to show tools from that category.

2. **Categorized Tools**  
   - Tools are grouped into three main categories:
     - **Content Generation**
     - **Image Generation**
     - **Conversational AI**

3. **Search-Like Experience**  
   - Sidebar links act as filters, enabling users to quickly find relevant AI tools.

4. **Responsive Layout**  
   - Uses a grid layout for the tool tiles.
   - Designed to adapt to various screen sizes.

5. **Easy to Extend**  
   - Add or remove categories by updating the `tools` object in the `<script>` section.
   - Customize the appearance by editing the embedded `<style>` block.

---

## Usage

1. **Open `index.html`**  
   - Clone or download the repository.
   - Open the `index.html` file in your browser.

2. **Browse Categories**  
   - Click any of the sidebar links (**Content Generation**, **Image Generation**, or **Conversational AI**) to view the tools in that category.

3. **Explore AI Tools**  
   - Each tile includes a tool name (a clickable link) and a brief description.
   - Clicking the link will open the tool's official website in a new tab.

4. **Customize**  
   - To add or remove categories/tools, edit the `tools` object in the `<script>` section.
   - Modify the `<style>` block to adjust the layout or theme.

---

## Folder Structure

```plaintext
.
├── index.html
└── README.md
