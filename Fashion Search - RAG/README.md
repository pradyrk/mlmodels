# Fashion Search AI using Myntra Dataset

**Project Description:**  
This project is based on an upGrad assignment on Semantic search, comprising three layers. It utilizes the Myntra dataset obtained from Kaggle, which was modified for the project. For more detailed information, refer to the Project Report: "Fashion Search AI."

Image Folder consists of Random 100- 200 images, if one wants to refer the original dataset and Image folder, then please refer to this link: https://www.kaggle.com/datasets/djagatiya/myntra-fashion-product-dataset

## Objectives:
- Develop a fashion query response system using AI models for detailed, user-friendly answers to fashion-related queries.
- Enhance the user experience by providing informative and contextually relevant responses to help users find fashion items based on preferences.

## Design:
- Search Layer: Retrieves relevant fashion items from the dataset using keyword matching or predefined criteria.
- Generation Layer: Uses advanced AI models like GPT-3.5 to generate detailed, context-aware responses in natural language.

## Implementation:
The implementation involved several steps, including data preprocessing, model integration, and query response generation.

### Data Preprocessing:
- Formatted CSV dataset for quality and readability.
- Replaced blank entries, standardized decimal points, and removed unnecessary
columns.
- Cleaned text columns by removing HTML tags and extra characters.
### Model Integration:
- Integrated AI models such as GPT-3.5 for generating responses.
- Processed queries through the model for detailed and contextually relevant replies.
### Query Response Generation:
- Processed user queries through both the search and generation layers.
- The search layer retrieved relevant items, while the generation layer provided
detailed AI-generated responses.

## Testing Queries:
Here are a few queries that were used to test the model:

- Query 1: What are the customization options and fabric details for the green and blue embroidered lehenga choli set with mirror work, including the blouse, lehenga, and dupatta?

- Query 2: What are the color details and key features of the grey colorblocked sweatshirt?

- Query 3: I'm searching for a versatile black leather jacket, suitable for various occasions and effortlessly complementing any outfit. Preferably in size XL.

- Query 4: What are the fabric details, customization options, and price for the off-white printed lehenga choli set with dupatta, including the blouse, lehenga, and dupatta?

- Query 5: Is the yellow and orange embroidered lehenga choli set with dupatta, including the ready-to-wear blouse and made-to-measure lehenga, available in other colors?

- Query 6: What are the key features and fabric composition of the navy blue cropped sweatshirt?

- Query 7: What are the color details and key features of the grey and green colorblocked sweatshirt?

## Challenges:
- Sequantial processing of text to embedding took long time

## Lessons Learned:

- The generation layer produces more detailed and comprehensible responses compared to the search layer.
- Unlike the search layer, which relies on keyword matching, the generation layer uses advanced AI like GPT-3.5 to deliver context-aware, dynamic replies.
- The generation layer offers nuanced explanations and engaging content in natural language, improving user experience.
- Its adaptability to various query formats and customization enhances its value for complex information tasks.
- Overall, while the search layer is efficient for retrieving information, the generation layer excels in providing high-quality, readable, and tailored responses.

## Future Scope:

- Adding documents to embeddings is a sequential process, can leverage a vector
store which can facilitate sync text as embeddings in parallel , for example Mosaic AI Vector store can sync the text to embeddings in the open storage delta format in few seconds - https://docs.databricks.com/en/generative-ai/vector-search.html
- Package all the components as chain and deploy as single unit
