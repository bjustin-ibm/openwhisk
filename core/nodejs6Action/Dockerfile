FROM nodejsactionbase

COPY setup.sh setup.sh

# put everything into one RUN in order to maximize space savings due to the
# significant amount of file deletes happening
RUN ./setup.sh

# See app.js
CMD node app.js
