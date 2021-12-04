Wersja “developerska” Dockerfile. Plik Dockerfile.dev1 Polecenia: Docker build -f Docekrfile.dev1 -t local/dev:1 . Docker run -it -p 3000:3000 local/dev1

Wykorzystanie wolumenów do śledzenia wpływu zmian na funkcjonowanie usługi. Pliki Dockerfile_dev3.yml a następnie docker-compose_old.yml Polecenia: Docker compose up --build

Rozwój usługi równolegle z testami. Plik docker-compose2.yml Polecenia: Docker compose up --build

Wersja “produkcyjna” Dockerfile a następnie docker-compose. Pliki Dockerfile.yml oraz docker-compose.yml Polecenia: Docker compose up --build
