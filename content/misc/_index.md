---
title: Miscellaneous
layout: "list"
type: "miscellaneous"
cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 3

# Optional header image (relative to `static/media/` folder).
header:
  caption: ''
  image: ''
---

<!-- <script>
  document.addEventListener("DOMContentLoaded", function () {
  
    const postsPerPage = 5; 
    const postList = document.querySelectorAll(".card-simple"); 

    const paginationContainer = document.createElement("div");
    paginationContainer.classList.add("pagination");

    if (postList.length === 0) {
      console.warn("⚠ No blog posts found.");
      return;
    }

    let totalPages = Math.ceil(postList.length / postsPerPage);
    let currentPage = 1;

    function showPage(page) {
      currentPage = page;
      postList.forEach((post, index) => {
        post.style.display = index >= (page - 1) * postsPerPage && index < page * postsPerPage ? "block" : "none";
      });
      updatePagination();
    }

    function updatePagination() {
      paginationContainer.innerHTML = ""; // clear pagination

      for (let i = 1; i <= totalPages; i++) {
        let pageElement = document.createElement("span"); // use <span> for non-clickable active page
        pageElement.innerText = i;
        pageElement.classList.add("page-number");

        if (i === currentPage) {
          pageElement.classList.add("active");
          paginationContainer.appendChild(pageElement);
        } else {
          let pageLink = document.createElement("a");
          pageLink.href = "#";
          pageLink.innerText = i;
          pageLink.classList.add("page-number");
          pageLink.onclick = function (e) {
            e.preventDefault();
            showPage(i);
          };
          paginationContainer.appendChild(pageLink);
        }
      }
    }

    // Insert Pagination Below Posts But Above Category Menu
    const wrappers_ = document.querySelectorAll(".universal-wrapper");
    let postContainer = null;
    console.log("wrappers", wrappers_);

    wrappers_.forEach(wrapper => {
      if (!wrapper.classList.contains("pt-3")) {
        postContainer = wrapper;
      }
    });

    const categoryMenu = document.querySelector(".blog-categories");

    if (postContainer) {
      postContainer.insertBefore(paginationContainer, categoryMenu);
    } else {
      console.error("Blog container not found! Could not inject pagination.");
    }

    // showPage(1); // Initialize first page
  });
</script> -->

<style>
  h1 {
    display: none;
  }

  blockquote {
    display: none;
  }

  .card-simple {
    margin-bottom: 20px;
  }

  .page-link {
    background-color: #f9f7f6;
    padding-top: 4px;
    /* padding-bottom: 9.5px; */
  }
</style>
