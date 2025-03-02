FROM jupyter/minimal-notebook:latest

# Copy the requirements file to the container and install dependencies
COPY requirements.txt /tmp/
RUN pip install --no-cache-dir -r /tmp/requirements.txt

# Optionally, copy your notebook if needed (or let Voila locate it in the repository)
# COPY cat_food_app.ipynb /home/jovyan/
