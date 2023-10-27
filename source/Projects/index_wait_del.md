---
title: Projects
date: 2023-10-14 00:45:26
academia: true
---

<style>
    .projects-table {
        width: 100%;
        border-collapse: collapse;
        margin: 0 auto;
    }
    .projects-table td {
        border: 0;

        vertical-align: middle;
    }
    .projects-table img {
        max-width: 200px;
        height: auto;
        margin-right: 20px;
    }
     .projects-table .paper p {
        text-align: left;
        margin: 0;
    }
</style>

<table class="projects-table">
    <tr>
        <td><img src="/img/OnlineOrder.png" alt="Abaltor"></td>
        <td class="paper">
                  <br>
                  <papertitle><b>OnlineOrder: A Spring and Hibernate based online food ordering system.</b></papertitle>
                  <em>Sep</em>, 2023
                  <br>
                  <a href="https://youtu.be/ZPjd3liwSkE" style="color:blue;">Video Introduction</a>
                  <p>Code Details (<a href="https://github.com/zli86605/onlineorder-Frontend" style="color:blue;">frontend</a> / <a href="https://github.com/zli86605/onlineorder-backend" style="color:blue;">backend</a>)</p>
                  <p>
                    <li>Implemented Rest API via Spring MVC including registration, menu searching , ordering, and checkout.</li>
                    <li>Utilized Hibernate to access and operate the data storage (menu, restaurants etc.)</li>
                    <li>Provided both authentication and authorization via Spring security to protect the application from malicious attacks.</li>
                    <li>Used the Spring framework core technologies to loosely decouple all the components in the application.</li>
                    <li>Build the client side with ReactJS and Ant Design to allow users to add items to the shopping cart and place orders.</li>
                  </p>
                  <br>
                </td>
    </tr>
    <tr>
        <td><img src="/img/Around.png" alt="RocketMq Operator"></td>
        <td class="paper">
                  <papertitle><b>Around: a Cloud and React based Social Network</b></papertitle><br>
                  <a href="https://youtu.be/ZPjd3liwSkE" style="color:blue;">Video Introduction</a>
                  <p>Code Details (<a href="https://github.com/zli86605/Around-Frontend" style="color:blue;">frontend</a> / <a href="https://github.com/zli86605/Around-Backend" style="color:blue;">backend</a>)</p>
                  <p></p>
                  <p>
                    <i>Frontend</i>
                    <li>Designed and implemented a social network web application with React JS. </li>
                    <li>Implemented features for users to create and browse posts and support search nearby posts.</li>
                    <li>Improved the authentication using token based registration/login/logout flow with React Router v4 and server-side user authentication with JWT.</li>
                    <i>BackEnd</i>
                    <li>Launched a scalable web service in Go to handle posts and deployed to Google Cloud (Google App Engine)</li>
                    <li>Used ElasticSearch (deployed to GCE) to provide search functions such that users can search recent posts and list personal posts.</li>
                  </p>
                  <br>
                </td>
    </tr>
    <tr>
        <td><img src="/img/autotest.png" alt="AutoTest"></td>
        <td class="paper">
                  <br>
                  <papertitle><b>Tinnews: a Tinder-like News Recommendation App</b></papertitle>
                  <br><br>
                  <p></p>
                  <p>
                    <li>Designed the Instagram Flavor News app based on Google Component Architectural MVVM Pattern</li>
                    <li>Implemented the bottom bar & page navigation using JetPack navigation component</li>
                    <li>Utilized Mindorks’s PlaceHolderView to support swipe gestures for liking/disliking the news</li>
                    <li>Built the Room Database with LiveData & ViewModel to support local cache and offline model</li>
                    <li>Integrated Retrofit and Rxjava to pull the latest news data from a RESTFUL endpoint (newsapi.org).</li>
                  </p>
                  <br>
                </td>
    </tr>
    <tr>
    <td><img src="/img/EventMaster.png" alt="EventMaster"></td>
        <td class="paper">
                  <br>
                  <papertitle><b>EventMaster</b></papertitle>
                  <br><br>
                  <p></p>
                  <p>
                    EventMaster is an event search platform that aggregates event
information from all around the United States. The project allows users to search for
upcoming events based on keywords, dates, and event types, as well as display detailed
information about related events. The project also features a bookmarking function, allowing
users to save their favorite events for easy access.
                  </p>
                  <br>
                </td>
    </tr>
    <tr>
    <td><img src="/img/CollegeAnalysis.png" alt="CollegeAnalysis"></td>
        <td class="paper">
                  <br>
                  <papertitle><b>College professional development analysis platform</b></papertitle>
                  <br><br>
                  <p>National-level Innovation Training Program -
                  <a href="http://bjcxcy.bjtu.edu.cn/Index/ItemDetail?id=3528e362-295d-4052-8f6a-4f0348313d50&_pageIndex=3595&_amp;_pageIndex=152&_eqid=8f8936dd0001b17200000003646f0237" style="color:blue;">link</a></p>
                  <br>
                  <p>
                    This project, which participated in the "Internet Innovation Competition,"
utilizes big data technology to gather information from recruitment websites and conduct
multi-dimensional statistical analysis, providing data support for college major development
and curriculum planning. And The project was awarded the "National College Student Innovation
Excellence Project";
                  </p>
                  <br>
                </td>
    </tr>
</table>
