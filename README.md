# Podcast Taxonomy

<a href="https://www.podcasttaxonomy.com" target="_blank">Podcast Taxonomy</a> is an international, multidisciplinary collaborative standard for recognizing roles and credits in podcast production. It consists of a list of roles and credits, and their description.

### Goals

1. Further professionalize the podcast industry by adopting a standard set of roles in podcast creation.
2. Help with job search and creation in podcasting, giving networks and independent creators a common list of known roles and job descriptions.
3. Ensure the taxonomy of podcast roles is inclusive, representing people of all backgrounds, including women, people of color, and marginalized voices.

### A Living, Breathing Document

This is a living, breathing document intended to be routinely updated via a convention of partners throughout podcasting known as the Podcast Taxonomy Consortium.

### Download the White Paper

The white paper in its most up to date state can be viewed via the <a href="https://drive.google.com/file/d/1pkkb6_Kg7Dc33IVgTopJO7QNka3FnH7m/view?usp=sharing" target="_blank">Google Doc</a>.

## JSON

The JSON file outlines the possible positions that creators can have in the podcasting industry in a structured and API-consumable way.

### Structure

The JSON file is formatted as an array of objects, each representing a single possible positiion in the industry. Groups are used to encapsulate and associate similar positions.
- `Position Title`  
- `Group Name` The general group the position falls under.
- `Description` A short explanation of the position and the tasks the position entails.
- `Example` A real life person who has (or has had) this position, usually including the relevant podcast or company name.

### Example
```JSON
[
  {
    "positionTitle": "Director",
    "groupName": "Creative Direction",
    "description": "The Director is the head of the entire creative production, from creative details to logistics. There is typically a single director for a production. This role is primarily seen in fiction podcasts.",
    "example": "Jenna Knorr for 'Welcome to Tinsel Town'"
  },
  {
    "positionTitle": "Assistant Director",
    "groupName": "Creative Direction",
    "description": "The Assistant Director is a liason between the director and the rest of the production, often coordinating the daily logistics of production. There may be multiple assistant directors on a project. This role is primarily seen in fiction podcasts.",
    "example": "William Wright for 'Inn Between'"
  }
]
```

### Usage
You can copy the JSON file in this repository into your app or website when defining the structure of creator roles, or use it as a visual reference when making business decisions including job hiring in the industry. You can also copy the spreadsheet cells directly from the <a href="https://drive.google.com/file/d/1pkkb6_Kg7Dc33IVgTopJO7QNka3FnH7m/view?usp=sharing" target="_blank">Google Doc</a>.

You can also import the JSON file directly into your website or app by referencing the static URL provided via this repository. In this case you should cache the results in your system for a reasonable period of time.


## More Information
Visit the official <a href="https://www.podcasttaxonomy.com" target="_blank">Podcast Taxonomy</a> website for more information.