# SDE1-Assignment-backend

### System Design
1.Upload API: Accepts CSV files, validates the formatting, and returns a unique request ID.

2.Image Processing Service: Asynchronously processes images by compressing them by 50% of their original quality.

3.Database: Stores product data and tracks the status of each processing request.

4.Status API: Allows users to query processing status using the request ID.

5.Webhook Handling: Processes callbacks from the image processing service.
