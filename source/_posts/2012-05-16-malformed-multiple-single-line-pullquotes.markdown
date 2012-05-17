---
layout: post
title: "Malformed multiple single line pullquotes"
date: 2012-05-16 21:58
comments: true
categories: 
---


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras ut sem vitae erat
convallis lobortis. Duis in turpis dolor, nec vehicula tellus. Quisque quis mi
nisi. Donec vel nisl id magna viverra fermentum no.

## though this paragraph's pullquote is malformed (and it still errors out correctly)

{% pullquote %} 
Pellentesque posuere felis sed felis interdum porttitor. Duis
ac nisi turpis.  Fusce et consectetur nulla. Phasellus sed nibh est, id tempus
enim. In hac habitasse platea dictumst. Aenean elementum nunc at tellus
venenatis molestie.  Pellentesque {" MWAHAAHA! I AM A MALFORMED PULLQUOTE AND I
NEVER END BUT ONLY LIQUID WILL CATCH ME MWAAHAHAHA!  lorem lorem, sollicitudin
at ultricies eget, pharetra nec nulla.  Ut laoreet vehicula tellus, non tempor
leo vulputate vel. Phasellus id orci leo. Curabitur commodo tincidunt arcu et
venenatis. Ut et magna in ligula eleifend tempor sit amet vel nulla. Praesent
id orci libero. In ut neque nec turpis porta faucibus eu venenatis ipsum.  
{% endpullquote %}


## The next paragraph is not affected! Whee!

{% pullquote %}
In egestas leo ac nisi vestibulum pulvinar. In lacinia dignissim mauris at
pharetra. Sed neque neque, {" rutrum in cursus ut, "} fringilla et metus. Vivamus nec
orci ipsum, vitae porttitor urna. Aliquam nisi eros, volutpat vel vestibulum
ac, suscipit nec lorem. Nullam enim arcu, lacinia non lacinia ac, aliquam sed
odio. Fusce vitae erat vulputate sapien dictum consequat vel vitae erat.
Integer mollis eros vestibulum enim facilisis laoreet. Suspendisse sed feugiat
libero. Mauris a tempor tortor. Proin tempus augue vitae urna malesuada
scelerisque.
{% endpullquote %}

{% pullquote %}
Sed eleifend tincidunt enim, at dapibus ligula auctor viverra. Donec nec lectus
at arcu consectetur auctor eu a diam {" In nec urna "} et arcu gravida interdum nec
a enim. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc accumsan
vehicula metus eu congue. Class aptent taciti sociosqu ad litora torquent per
conubia nostra, per inceptos himenaeos. Integer non urna dolor. In hendrerit
dignissim lacus, quis vulputate mauris tempor vel. Nullam molestie pharetra
lacus nec tempus. Phasellus id ante vitae augue suscipit rhoncus. Donec at erat
odio. Mauris ut feugiat sapien.
{% endpullquote %}
