---
layout: page
title: Contacts
permalink: /contacts/
<!---banner_image: sample-banner-image-2.jpg-->
---

<table style="width:100%; text-align: center">
  <tr>
    <th style="width:50%; border: 0; font-weight: bold;" align="center">Work email</th>
    <th style="width:50%; border: 0; font-weight: bold;" align="center">Personal email</th> 
  </tr>
  <tr>
    <td style="width:50%; border: 0;" align="center">
		<a title="Oleksandr.Kazymyrov@evry.com" href="mailto:Oleksandr.Kazymyrov@evry.com" target="_blank">Oleksandr.Kazymyrov@evry.com</a>
    </td>
    <td style="width:50%; border: 0;" align="center">
		<a title="okazymyrov@gmail.com" href="mailto:okazymyrov@gmail.com" target="_blank">okazymyrov@gmail.com</a>
    </td> 
  </tr>
</table>

---
<table style="width:100%; text-align: center">
  <tr>
    <th style="width:50%; border: 0; font-weight: bold;" align="center">Mobile phone</th>
    <th style="width:50%; border: 0; font-weight: bold;" align="center">Networks</th> 
  </tr>
  <tr>
    <td style="width:50%; border: 0;">
    		<a title="+47 47 44 21 78" href="tel:+4747442178" target="_blank">+47 47 44 21 78</a>
    </td>
    <td style="width:50%; border: 0;">
		{% capture social_media_li %}
		<ul class="social-media">
		    {% if site.theme.social.linkedin %}
		    <li>
		        <a title="{{ site.theme.social.linkedin }} on LinkedIn" 
		            href="https://linkedin.com/in/{{ site.theme.social.linkedin }}" 
		            class="linkedin wc-img-replace" target="_blank">LinkedIn</a>
		    </li>
		    {% endif %} 
		    
		    {% if site.theme.social.gplus %}
		    <li>
		        <a title="{{ site.theme.social.gplus }} on Google Plus" 
		            href="https://plus.google.com/{{ site.theme.social.gplus }}" 
		            class="google wc-img-replace" target="_blank">Google</a>
		    </li>
		    {% endif %}

		    {% if site.theme.social.facebook %}
		    <li>
		        <a title="{{ site.theme.social.facebook }} on Facebook" 
		            href="https://facebook.com/{{ site.theme.social.facebook }}" 
		            class="facebook wc-img-replace" target="_blank">Facebook</a>
		    </li>
		    {% endif %}

		    {% if site.theme.social.github %}
		    <li>
		        <a title="{{ site.theme.social.github }} on Github" 
		            href="https://github.com/{{ site.theme.social.github }}" 
		            class="github wc-img-replace" target="_blank">Github</a>
		    </li>
		    {% endif %} 
		</ul>
		{% endcapture %}{{ social_media_li | strip_newlines }}
    </td> 
  </tr>
</table>

---

<h1>Visiting Address</h1>
<iframe width="100%" height="350" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://www.google.com/maps?t=m&amp;q=Evry+AS,+Sandslimarka+260,+5254+Sandsli,+Norway&amp;ie=UTF8&amp;hnear=Evry+AS,+Sandslimarka+260,+5254+Sandsli,+Norway&amp;z=16&amp;ll=60.2982763,5.2788235&amp;iwloc=near&amp;output=embed"></iframe>
