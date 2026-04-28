🔧 Workflow: Automated LinkedIn AI Trend Posting

Step 1: Trigger the Workflow

Use Schedule Trigger (auto) or Manual Trigger
Starts the automation process

Step 2: Fetch Topics from Sheet

Connect Google Sheets
Read rows containing AI topics (e.g., 3 topics)

Step 3: Get Latest Trends Data

Use HTTP Request (API like Tavily or similar)
Fetch latest info/news about each topic

Step 4: AI Agent Processing

AI Agent analyzes topics + fetched data
Generates structured LinkedIn-ready content

Step 5: Generate Image Prompt

Convert content into a prompt for image generation
Keeps visuals relevant to the topic

Step 6: Create AI Image

Use image generation API
Generate post image automatically

Step 7: Convert Image Format

Convert Base64 → File (needed for upload)

Step 8: Post to LinkedIn

Create LinkedIn post
Attach generated text + image

Step 9: Update Sheet (Tracking)

Mark topic as “Done” in Google Sheets
Prevents duplicate posting

Step 10: End Workflow

No operation / workflow stops
