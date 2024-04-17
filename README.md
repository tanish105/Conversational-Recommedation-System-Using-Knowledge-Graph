Overview

Knowledge graphs serve as invaluable assets for disseminating structured and semantically enriched data to both humans and machines, ensuring accuracy and reliability. However, conventional approaches to generating knowledge graphs from existing benchmark data sources often fail to highlight crucial relationships between entities. In this project, we propose a strategy to enrich a knowledge graph by resolving multiple entity relationships generated from the ReDial movie dataset.
Key Features

    Identification of missing entities and their corresponding relationships.
    Leveraging the publicly available large TMDb dataset to align additional information such as genre, director, actor, writer, and year as nodes.
    Introducing bidirectional links to semantically enrich the knowledge graph.

Validation Approach

Validating a knowledge graph is crucial to ensure its accuracy and reliability. In this project, we validate the knowledge graph by extracting triplets in the format (movie, relationship, genre) from the graph. These triplets are validated using IMDb, a vast repository of movie details, and the Gemini Generative AI model.
Results

The accuracy of the extracted triplets is computed, and the results indicate an improvement in the knowledge graph generation strategy. IMDb emerges as an efficient validator for our approach.
