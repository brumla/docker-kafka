# Docker Compose file for Kafka development instance
This is simple `docker-compose.yaml` file which can be used to start simple unsecure development
instance of Apache Kafka (the Bitnami version in this case).

The reason for creation of this project is fact, that one must use different sources to collect
the right setup of the `docker-compose.yaml` file to have it working correctly.

# Usage

1. Clone this repository
2. Inside the repo folder run `docker-compose -d up`
3. Enjoy

This setup was tested with the .NET 7 based producer and subscriber projects based on the
examples on Bitnami website (see their tutorials).

| Important: I am not anyhow related to Apache Kafka and Bitnami company.

# Licence

Docker Compose file for Kafka
Copyright (C) 2023 Brumla

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program; if not, write to the Free Software Foundation,
Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
