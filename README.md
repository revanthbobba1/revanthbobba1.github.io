# revanthbobba1.github.io
The Official Cary Bengals Fantasy Football League Website


## Update Guide


### Weekly Preview/Recap

For every new week:

1. Add the new week to the selector, and make it active in the selector (selected="selected")
2. Create a new "section" object to place the new weeks content in
3. Remove "active" in the class options from the previous week and add it into the new week
    ie: If we are moving from week 1 to 2, the week 1 "section" object will look like: section id="week1" class="tab-content active"
        Remove the "active" keyword from the class and add it into the new week's "section" -> id="week1" class="tab-content" and id="week2" class="tab-content active"
4. Ensure to follow the structure of the previous weeks to ensure content is organized