# Use lightweight Nginx image
FROM nginx:alpine

# Remove default nginx website
RUN rm -rf /usr/share/nginx/html/*

# Copy your HTML and CSS files into nginx web directory
COPY . /usr/share/nginx/html/

# Expose port 80
EXPOSE 80
