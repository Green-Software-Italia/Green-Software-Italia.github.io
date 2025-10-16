---
title: "Green Software Italia 🌱"
layout: home
permalink: /
author_profile: false
tagline: "Una community per un futuro digitale sostenibile e inclusivo."
tagline-as-title: true
header:
  overlay_image: /assets/images/header-home.webp
  overlay_filter: 0.5
  actions:
  - label: "Cosa facciamo"
    url: "#cosa-facciamo"
    style: "inverse"
  - label: "Contribuisci anche tu"
    url: "#contribuisci-anche-tu"
    style: "light-outline"
countdown: true
meetup_link: "https://tinyurl.com/gsi-3-meetup"
calendar_link: 
meetup_day: 20
meetup_month: 11
meetup_year: 2025
meetup_hour: 18
meetup_minute: 45
---
{% if page.countdown == true %}
<div class="countdown_section">
    <h2> Il prossimo meetup inizia tra </h2>
    <div id="meetup-countdown" class="countdown-dark">
    </div>
    <div class="button_group">
        <a class="btn btn--inverse" href="{{ page.meetup_link }}" target='_blank'>Iscriviti al meetup
        </a>
        {% if page.calendar_link %}
        <a class="btn btn--light-outline" href="{{ page.calendar_link }}" target='_blank'>Aggiungi al calendario
        </a>
        {% endif %}
    </div>
</div>
{% endif %}

<div class="home_section">

    <h2> Chi siamo </h2>

    <p class="text-center">Green Software Italia è una community dedicata a esplorare l’impatto delle scelte tecnologiche e aziendali sul pianeta e sulla società. In un mondo sempre più digitale, crediamo sia fondamentale promuovere un approccio consapevole e responsabile all’innovazione, integrando sostenibilità, efficienza ed equità.
</p>

    <div class="card_list">
        {% include team_card.html name="Valeria Salis" imgsrc="/assets/images/img_Vale.webp" url="https://www.linkedin.com/in/valeria-salis"%}
        {% include team_card.html name="Chiara Corrado" imgsrc="/assets/images/img_Chiara.webp" url="https://www.linkedin.com/in/chiaracorrado"%}
        {% include team_card.html name="Ludovica Bonaldo" imgsrc="/assets/images/img_Ludo.webp" url="https://www.linkedin.com/in/ludovica-bonaldo"%}
        {% include team_card.html name="Andrea Saltarello" imgsrc="/assets/images/img_AndreaS.webp" url="https://www.linkedin.com/in/andysal"%}
        {% include team_card.html name="Mich Murabito" imgsrc="/assets/images/img_Mich.webp" url="https://www.linkedin.com/in/mich-murabito"%}
        {% include team_card.html name="Andrea Bordoni" imgsrc="/assets/images/img_AndreaB.webp" url="https://www.linkedin.com/in/andreabordoni"%}
    </div>
</div>

<div class="home_section">

    <h2 id="cosa-facciamo"> Cosa facciamo 🚀 </h2>

    <div class="card_list">

        <div class="card_pair">
            {% include info_card.html icon="fas fa-users-rays" title="Meetup ed eventi" description="per condividere esperienze e best practice sul Green Software"%}

            {% include info_card.html icon="fas fa-person-chalkboard" title="Workshop e talk" description="con esperti del settore su sviluppo sostenibile, cloud green, accessibilità e innovazione responsabile"%}
        </div>

        <div class="card_pair">
            {% include info_card.html icon="fas fa-book-open" title="Contenuti e risorse" description="per diffondere conoscenze su software sostenibile e buone pratiche di sviluppo"%}

            {% include info_card.html icon="fas fa-hand-holding-hand" title="Collaborazioni" description="con community, aziende e università per amplificare la cultura del Green IT"%}
        </div>

    </div>
</div>


<div class="home_section" id="bg">
    <h2> I nostri valori 🎯 </h2>

    <div class="card_list">
        <div class="card_pair">
            {% include info_card.html icon="fas fa-seedling" title="Sostenibilità digitale" description="Ridurre lo spreco di risorse e sviluppare soluzioni più efficienti"%}

            {% include info_card.html icon="fas fa-universal-access" title="Inclusione e accessibilità" description="Garantire che la tecnologia sia utilizzabile da tutti"%}
        </div>

        <div class="card_pair">
            {% include info_card.html icon="fas fa-earth-europe" title="Innovazione responsabile" description="Ogni scelta tecnologica ha un impatto e va considerata con attenzione"%}

            {% include info_card.html icon="fas fa-book-open-reader" title="Formazione e consapevolezza" description="Ogni scelta tecnologica ha un impatto e va considerata con attenzione"%}
        </div>
    </div>
</div>

<div class="home_section">

    <h2 id="contribuisci-anche-tu"> Contribuisci anche tu alla sostenibilità del tech 🫵 </h2>

    <div class="contrib_section">
        
        <img src="/assets/images/we-want-you.webp" alt='Immagine con su scritto "We want you" e il logo della community Green Software Italia'/>
        
        <div>
            {% include link_card.html url="https://sessionize.com/green-software-italia-meetup-1/" title="Call for Speaker" description="Se vuoi portare un <strong>talk</strong> a uno dei prossimi meetup"%}

            {% include link_card.html url="https://forms.gle/87rN6sE4u7adu2BZA" title="Call for Spaces" description="Se non hai tempo, ma puoi offrire uno <strong>spazio</strong> dove ospitare un meetup "%}

            {% include link_card.html url="https://forms.gle/7cPuexh3WT5LSn3N7" title="Call for Contributors" description="Se vuoi dare una mano con <strong>eventi</strong>, <strong>contenuti</strong>, <strong>strumenti</strong> o <strong>advocacy</strong>"%}
        </div>
    </div>
</div>
