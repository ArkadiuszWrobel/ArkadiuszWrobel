# Trello API Testing


### Environment setup
Setting up variables like baseURL, trello token and key.

![285656220-8c4e7cbb-5e80-4fa0-b7b7-740e5b31a61e](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/07e26652-d143-4eab-b251-7141ad34ceb8)

### Using method GET to get boards list for my account. Response Code 200 means that we succeded.

![get](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/f03a75eb-4c15-49b6-af1d-5ae5ad66d931)

### Time to post a new board on my account. Setting up board's title into variable.

![trell env](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/13d28a1b-760d-432e-830a-4dcc7ccbcf57)

### Time for posting new board. I have also wrote code that saves reponse board ID to variable so I can operate faster.

![POST](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/992f380d-1360-49a1-ac71-068b9e8b9d38)

### If we check Trello's website, we can see new board with our custom name.

![postBoard](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/0bf6f535-e2c2-42fe-8090-e0d64e3bb984)

### Time to update the name. I am going to use PUT method to update title and description. For that we need variables of updated title and description.

![put var](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/e1c3f61f-23c8-4ed3-b500-71e93953e540)

### Let's run PUT method. As we can see on the pictures below title and desc have updated.

![PUT](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/07630516-66e1-405e-a33a-1e99846589f8)
![put board](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/90a1aebc-271a-4c74-8d59-cd7bb9283f67)

### Time to remove board using boardID variable.

![DELETE](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/e05dcd42-15c2-4c5b-a7cd-6f08b9a6b5dc)

### It return's null value so board should be removed. Let's check the Trello's website also.![delete board](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/01cc1675-5c79-4a72-93c5-019243885697)
