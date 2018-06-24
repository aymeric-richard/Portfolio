---
layout: default
---

<head>
		<!-- amCharts javascript sources -->
		<script type="text/javascript" src="https://www.amcharts.com/lib/3/amcharts.js"></script>
		<script type="text/javascript" src="https://www.amcharts.com/lib/3/radar.js"></script>
		<script type="text/javascript" src="https://www.amcharts.com/lib/3/themes/dark.js"></script>
		

		<!-- amCharts javascript code -->
		<script type="text/javascript">
			AmCharts.makeChart("chartdiv",
				{
					"hideCredits":true,
					"type": "radar",
					"categoryField": "Skill",
					"startDuration": 1,
					"theme": "dark",
					"graphs": [
						{
							"balloonColor": "",
							"bullet": "diamond",
							"bulletBorderColor": "undefined",
							"bulletBorderThickness": 0,
							"bulletColor": "#FFFFFF",
							"bulletHitAreaSize": 0,
							"fixedColumnWidth": 0,
							"fontSize": 9,
							"id": "AmGraph-1",
							"lineAlpha": 0.94,
							"lineColor": "#FFFFFF",
							"negativeBase": -1,
							"periodSpan": 0,
							"tabIndex": -1,
							"valueField": "2018"
						},
						{
							"bullet": "diamond",
							"bulletBorderThickness": 0,
							"bulletColor": "#B5E853",
							"fixedColumnWidth": -4,
							"id": "AmGraph-2",
							"lineColor": "#B5E853",
							"maxBulletSize": 48,
							"minBulletSize": 6,
							"periodSpan": 0,
							"title": "graph 2",
							"valueField": "2020"
						}
					],
					"guides": [],
					"valueAxes": [
						{
							"axisTitleOffset": 20,
							"id": "ValueAxis-1",
							"minimum": 0,
							"axisAlpha": 0.15
						}
					],
					"allLabels": [],
					"balloon": {},
					"titles": [],
					"dataProvider": [
						{
							"2018": "17",
							"2020": "20",
							"Skill": "C# .NET"
						},
						{
							"2018": "10",
							"2020": "13",
							"Skill": "Unity 3D"
						},
						{
							"2018": "13",
							"2020": "16",
							"Skill": "ASP .NET MVC"
						},
						{
							"2018": "15",
							"2020": "15",
							"Skill": "Git"
						},
						{
							"2018": "14",
							"2020": "14",
							"Skill": "GNU / Linux"
						}
					]
				}
			);
			AmCharts.makeChart("humanskills",
				{
					"hideCredits":true,
					"type": "radar",
					"categoryField": "Skill",
					"startDuration": 1,
					"classNamePrefix": "humanskills",
					"theme": "dark",
					"graphs": [
						{
							"balloonColor": "",
							"bullet": "diamond",
							"bulletBorderColor": "undefined",
							"bulletBorderThickness": 0,
							"bulletColor": "#FFFFFF",
							"bulletHitAreaSize": 0,
							"dashLength": 3,
							"fixedColumnWidth": 0,
							"fontSize": 16,
							"id": "AmGraph-1",
							"lineAlpha": 0.94,
							"lineColor": "#FFFFFF",
							"negativeBase": -1,
							"periodSpan": 0,
							"tabIndex": -1,
							"valueField": "2018"
						},
						{
							"bullet": "diamond",
							"bulletBorderThickness": 0,
							"bulletColor": "#B5E853",
							"fixedColumnWidth": -4,
							"id": "AmGraph-2",
							"lineColor": "#B5E853",
							"maxBulletSize": 48,
							"minBulletSize": 6,
							"periodSpan": 0,
							"title": "graph 2",
							"valueField": "2020"
						}
					],
					"guides": [],
					"valueAxes": [
						{
							"axisTitleOffset": 20,
							"id": "ValueAxis-1",
							"minimum": 0,
							"axisAlpha": 0.15
						}
					],
					"allLabels": [],
					"balloon": {},
					"titles": [],
					"dataProvider": [
						{
							"2018": "10",
							"2020": "14",
							"Skill": "Méthodes Agiles"
						},
						{
							"2018": "18",
							"2020": "18",
							"Skill": "Créativité"
						},
						{
							"2018": "18",
							"2020": "18",
							"Skill": "Humour"
						},
						{
							"2018": "13",
							"2020": "15",
							"Skill": "Multipotentialité"
						},
						{
							"2018": "16",
							"2020": "16",
							"Skill": "Persévérance"
						}
					]
				}
			);
		</script>
</head>

# Compétences

## Comparaison des niveaux de compétences
<div id="chartdiv" style="width: 50%; height: 400px; background-color: none; float: left;" ></div>
<div id="humanskills" style="width: 50%; height: 400px; background-color: none;" ></div>

Niveau actuel 2018 en blanc, <span style="color: #B5E853">niveau prévu pour 2020 en vert</span>.

## Compétences Techniques

<img src="{{ site.imagesLocation | absolute_url}}/icon_csharp.png" class="icon"/>
[C# .NET]({{ site.skillsLocation | append: site.technicalSkillsLocation |  absolute_url }}/csharpdotnet)
<p class="short-description">Le langage qui Pèse dans le game</p>

<img src="{{ site.imagesLocation | absolute_url}}/icon_unity.jpg" class="icon"/>
[Unity 3D]({{ site.skillsLocation | append: site.technicalSkillsLocation |  absolute_url }}/unity3d)
<p class="short-description">Jouer c'est bien, faire jouer c'est mieux</p>

<img src="{{ site.imagesLocation | absolute_url}}/icon_asp.jpg" class="icon"/>
[ASP.NET MVC]({{ site.skillsLocation | append: site.technicalSkillsLocation |  absolute_url }}/aspnetmvc)
<p class="short-description">La référence pour le web avec C\# </p>

<img src="{{ site.imagesLocation | absolute_url}}/icon_git.png" class="icon"/>
[Git]({{ site.skillsLocation | append: site.technicalSkillsLocation |  absolute_url }}/git)
<p class="short-description">L'incontestable gestionnaire de code source</p>

<img src="{{ site.imagesLocation | absolute_url}}/icon_linux.png" class="icon"/>
[GNU / Linux]({{ site.skillsLocation | append: site.technicalSkillsLocation |  absolute_url }}/linux)
<p class="short-description">Software is like sex, it's better when it's free</p>
<!-- [Autres Compétences]({{ site.skillsLocation | append: site.technicalSkillsLocation |  absolute_url }}/minorskills) -->
<!-- Ici, mettre un lien avec une ancre par skill minor -->

## Compétences Transverses

<img src="{{ site.imagesLocation | absolute_url}}/icon_agility.png" class="icon"/>
[Méthodes Agiles]({{ site.skillsLocation | append: site.humanSkillsLocation |  absolute_url }}/agility)
<p class="short-description">A qui ?</p>

<img src="{{ site.imagesLocation | absolute_url}}/icon_creativity.gif" class="icon"/>
[Créativité]({{ site.skillsLocation | append: site.humanSkillsLocation |  absolute_url }}/creativity)
<p class="short-description">La clé de la réussite, je vous en fait un double ?</p>

<img src="{{ site.imagesLocation | absolute_url}}/icon_humor.gif" class="icon"/>
[Humour]({{ site.skillsLocation | append: site.humanSkillsLocation |  absolute_url }}/humor)
<p class="short-description">Comment dire n'importe quoi mais pas à n'importe quel moment</p>

<img src="{{ site.imagesLocation | absolute_url}}/icon_multipotentialite.png" class="icon"/>
[Multipotentialité]({{ site.skillsLocation | append: site.humanSkillsLocation |  absolute_url }}/multipotentialite)
<p class="short-description">Pas de passion, trop de passion. Trop de passion, trop de passion</p>

<img src="{{ site.imagesLocation | absolute_url}}/icon_perseverance.png" class="icon"/>
[Persévérance]({{ site.skillsLocation | append: site.humanSkillsLocation |  absolute_url }}/perseverance)
<p class="short-description">Ma réussite personnelle et professionnelle</p>

## Langues

<img src="{{ site.imagesLocation | absolute_url}}/flag_fr.png" class="icon"/>
**Français**
<p class="short-description">Langue maternelle</p>

<img src="{{ site.imagesLocation | absolute_url}}/flag_enus.png" class="icon"/>
**Anglais**
<p class="short-description"><abbr title="Read">r</abbr><abbr title="Write">w</abbr><abbr title="Execute. J'entends par là, travailler en anglais">x</abbr> fluent - Toeic : 785</p>

<img src="{{ site.imagesLocation | absolute_url}}/flag_brazil.png" class="icon"/>
**Portugais**
<p class="short-description">Je connais des mots. Au cours de cette année je vais apprendre à faire des phrases pour de courtes discutions.</p>