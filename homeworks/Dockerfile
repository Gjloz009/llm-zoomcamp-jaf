FROM ollama/ollama

# Set the working directory to where Ollama expects its files
WORKDIR /root/.ollama

# Copy the manifest files
COPY ./ollama_files/models/ ./models/

EXPOSE 11434

# Set the default command to run Ollama
#CMD ["ollama", "serve"]