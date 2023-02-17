# Zoom Engage

<img width="822" alt="Screen Shot 2023-02-16 at 5 03 26 PM" src="https://user-images.githubusercontent.com/66803124/219512395-1fd8852c-70e2-4f8a-a8b7-2a58adb528f5.png">

Engage busts out of the black square grid and allows the user to show their creativity while increasing productivity. Engage will make collaboration easier, more effective, and much more enjoyable.

<img width="477" alt="Screen Shot 2023-02-16 at 6 42 15 PM" src="https://user-images.githubusercontent.com/66803124/219512860-554fac8d-b28e-47bc-a9aa-86865b73b156.png">

As a remote worker, I am constantly thinking of ways to improve video conferencing. 

The large black boxes on my screen all day have always felt uninspiring. Seeing online classrooms is even more jarring. In school, the teachers would always decorate their rooms with so much color and vibrance. Where is that vibrance now? 

With Zoom Engage, I wanted to bring it back. In doing so, Zoom can leverage the preference shown to its platform to pull ahead in market share.

<img width="480" alt="Screen Shot 2023-02-16 at 6 41 09 PM" src="https://user-images.githubusercontent.com/66803124/219512750-093f8197-0b8d-4f12-8249-a4cf22a2b0ac.png">

SO many companies are trying to compete in the video conferencing arena. But they all use the same uninspired black boxes. 

<img width="733" alt="Screen Shot 2023-02-16 at 6 48 37 PM" src="https://user-images.githubusercontent.com/66803124/219513706-23a7be51-03ed-44fd-b39f-77054cdf803d.png">

##### What if we broke away from this? <br>
##### What if we let the user decide what their work environment or classroom would look like? <br>
##### How much more creativity and productivity could we generate? <br>
##### How much much more preference for the Zoom platform could we foster? <br>
#### I am ready to find out. <br>

# Introducing Zoom Engage

<img width="480" alt="Screen Shot 2023-02-16 at 5 29 50 PM" src="https://user-images.githubusercontent.com/66803124/219513853-ebe698be-e923-44fc-a08f-819d10536a14.png">

<img width="482" alt="Screen Shot 2023-02-16 at 5 29 32 PM" src="https://user-images.githubusercontent.com/66803124/219513866-2800e45a-1759-41e4-87f6-18f21ce45a93.png">

## For a new remote environments, whether that is at work, in the classroom, or catching up with friends, everyone deserves a place where they can feel like themselves and express their creativity. Not be boxed in. 

<img width="477" alt="Screen Shot 2023-02-16 at 5 30 18 PM" src="https://user-images.githubusercontent.com/66803124/219513885-73e25556-6297-49ee-9d14-f6d77818553a.png">


<img width="481" alt="Screen Shot 2023-02-16 at 5 30 32 PM" src="https://user-images.githubusercontent.com/66803124/219513900-ea32c2a7-6612-4c60-9c7a-b9892f85c549.png">


<img width="750" alt="Screen Shot 2023-02-16 at 8 23 22 PM" src="https://user-images.githubusercontent.com/66803124/219525615-2735fc31-edef-4c9b-8fea-b7469843353c.png">

Zoom API: The Zoom API (Application Programming Interface) is a set of rules and protocols that allows software applications to interact with the Zoom platform. This solution uses the Zoom API to retrieve the list of participants and their current status (mic on/off, video on/off, screen sharing on/off).

Zoom video SDK: Another option for creating a custom video conferencing solution with Zoom is to use the Zoom video SDK (Software Development Kit). The video SDK provides more control over the video conferencing experience and allows for the creation of custom interfaces and features.

Programming languages: This solution requires a programming language to implement the logic for calculating participant priorities, determining box sizes, and adjusting box sizes based on user input. The choice of programming language would depend on the platform and tools being used to develop the solution. Languages that interact with the Zoom API include Python, Java, and JavaScript. I chose Python for this implementation since it is the langauage I have the most experience in. 

User interface: This solution involves creating a custom user interface that allows the user to resize the boxes of the participants in a Zoom call.

Web technologies: It would likely involve the use of web technologies such as HTML, CSS, and JavaScript to create the user interface and handle user input.

#### To create the Grid Resizing Solution:
1. Retrieve the list of participants and their current status (mic on/off, video on/off, screen sharing on/off) from the Zoom API.
2. Calculate the priority for each participant based on their status, following the order given in the prompt (screen share > mic+camera on > mic on > camera on > mic+camera off).
3. Sort the list of participants based on their priority, from highest to lowest.
4. Determine the desired size of each box for each participant, based on their priority. For example, the largest screen share participant might get 2/3 of the screen, while the smallest mic+camera off participant might get 1/6 of the screen.
5. Allow the user to change the size of each box individually by dragging its borders. As the user changes the size of a box, adjust the size of the other boxes accordingly to maintain the desired proportions.
6. If the user does not manually resize any boxes, display the boxes with the predetermined sizes based on their priority.








