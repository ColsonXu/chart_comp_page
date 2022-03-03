---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

This is the website for [ICPR 2022 CHART Competition](https://chartinfo.github.io/). Under construction.

<button class="btn js-toggle-dark-mode">Dark Mode</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Dark Mode';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Light Mode';
  }
});
</script>

## Event Schedule

Event | Deadline
----- | ---------
Registration Opens | February 21, 2022
Training Data Release | February 23, 2022
Test Data Release | May 1, 2022
Half Page Description of System due | May 6, 2022
Results due by email | May 8, 2022
Full report due | May 8, 2022
Winners Announcement | May 2022

## Tasks
![Tasks](https://chartinfo.github.io/img/tasks.png)
