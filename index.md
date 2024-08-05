# Bluestamp Magic Mirror
A smart mirror is an innovative device that integrates a reflective surface with a digital display, providing real-time information such as weather updates, news, and personal notifications while maintaining its traditional function. I think that the hardesat part of making of this was getting the vnc connected because i had to install.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Vivan B | Prospect Highschool | Aeronautical Engineering | Incoming Freshman

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/ORGMPVJyOLk?si=q19fnz-xWn8Wa-4r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- I have got the google assistant working and spotify working this is basically what i will stick with this for now
- I was very surpised at how much harder getting the modules to work was than just the baseline
- I installed a bad module and it made my mirror not work so i had to delete the MagicMirror software and reinstall it, there were also multiple times when installing google assistant where i did not know what to do so i had to spend 10 to 15 minutes just to find a button.
- i just need to get the frame and the mirror film on the display to make it a mirror and then ill be done

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/96U5nTjL_Ug?si=n02NEri9h8aJAPGn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

i used two Components in my first milestone a raspberry pi and an lcd display to code the raspberry pi i had to install the thirty-two-bit raspberry pi os onto a micro sd card now that i had everything installed i could run a few commands the first one i ran was
```
git clone https://github.com/MichMich/MagicMirror
```
this command gets the file information from github, then i ran
```
cd MagicMirror/
```
this command compiles all the information from the first command into a file with that name, after that we need to install all of the information using the command below
```
npm run install-mm
```
After this, you have all this data on your Rasberry Pi you have to get it from the configuration file which contains all Magic Mirrors software code. That is done by entering
```
cp config/config.js.sample config/config.js
```
now we need to tell the computer to use all the information and do something with it in this case we are telling it to open up the magic mirror software by running the code
```
npm run start
```
now the magic mirror software boots up now because it is just the baseline it only shows the date, time, weather, and news. I hope to add more modules like a google assistant and spotify

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Raspberry Pi | Programming the mirror | $95.19 | <a href=" https://www.amazon.com/RasTech-Raspberry-Starter-Heatsink-Screwdriver/dp/B0C8LV6VNZ/ref=sr_1_4?crid=3506HY00MCGVM&dib=eyJ2IjoiMSJ9._zkM62vSQ8p7tNr88715LdMv_qHh72Je-tkF9PXEa3chDE53QT4aZu4AGAb4ihE61QY4ZD55nKF6Fp2Kfs8t7AbafM_JrlJFfHo9OB4eAVGqa0EB-7aoBQHPmhKHZ2MW8ny-Kd44bMVlVxPlTWVk5YHIN5P3uKVqrE5Dcal0rKkHny-O6Xyb5ux2AOU6OwVbkag_bqBX66RQNRrgBuz-0pS43mcx93IZTQA9R8NaJJypYU2HAycp-XicTFmyU60a01Nfm9iuyo6B9yA8ppN3OQQyJ-NQ9xyNPxfTLwkqtng.yAYpU6outhQcZmOZhN9Wb6yTw7A85CNUbXZguGInZNg&dib_tag=se&keywords=raspberry%2Bpi%2Bkit&qid=1718848547&s=electronics&sprefix=rasbperry%2Bpi%2Bkit%2Celectronics%2C83&sr=1-4&th=1"> Link </a> |
| LCD Display | showing the information that we want it to | $41.35 | <a href=" https://www.amazon.com/Hosyond-Display-1024×600-Capacitive-Raspberry/dp/B09XKC53NH/ref=sr_1_3?crid=1KKB9WC62OIAD&keywords=raspberry%2Bpi%2Bips&qid=1685911698&s=electronics&sprefix=raspberry%2Bpi%2Bips%2B%2Celectronics%2C87&sr=1-3&th=1#customerReviews"> Link </a> |
| Keyboard and mouse | If you want to type on the display without connecting it to the computer again | $19.99 | <a href=" https://www.amazon.com/gp/product/B07XDWCLYF/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1"> Link </a> |
