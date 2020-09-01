---
title: Hiring Across Borders
layout: default
datatable: true
---

# 🌍 Hiring Across Borders 

This is a list of companies that are able to support new employees who are immigrating. This means that these companies are able to help new employees get visas or work permits, either through "sponsorship" or simply by assissting with necessary paperwork. 

This is motivated in large part by conversations I've had over the last several weeks: I’ve talked to more and more American tech workers who are curious about moving abroad, with increasing urgency. But I expect it will be broadly helpful to anyone who is interested in moving and exploring new countries. 

The list below is sortable and filterable, by role and location: 

Filter me: <input type="text" disabled=true id="filter" placeholder="Filter..." autofocus /><br/>
<table id="filterable" class="overview sortable-table">
    <thead>
        <tr>
            <th>Company ⇅</th>
            <th>Location ⇅</th>
            <th>Hiring for... ⇅</th>
            <th>Contact Info ⇅</th>
        </tr>
    </thead>

    <tbody>
        {% for c in site.data.companies %}
        <tr>
            <td>{{ c.name }}</td>
            <td>{{ c.location }}</td>
            <td>{{ c.hiring }}</td>
            <td>{{ c.url }}</td>
        </tr>
        {% endfor %}
    </tbody>
</table>

## Add your company 

The easiest way to add your company is to open a PR on 
<a href="https://github.com/tessr/hiring-across-borders">the Github repo</a>
 hosting this page, and 
 <a href="https://github.com/tessr/hiring-across-borders/blob/main/_data/companies.yml">add your info to the data.yml file</a>. 
 (That way, you can also remove and update your data.) 
 However, if you’re not comfortable using Github, feel free to 
 <a href="https://twitter.com/_tessr">DM me</a> 
 and I’ll add your info myself :) 
 
<br/><br/><br/><br/>
