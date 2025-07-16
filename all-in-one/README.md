<img src="https://github.com/user-attachments/assets/23ea0bbb-0e7e-4aa5-b470-976caf9869f6" height=200>

# homer 11 preview (all-in-one)
The ultimate  **homer** demo w/ sample _hep traffic, logs, traces and metrics_ - _batteries included!_ :battery::battery:

> All the backend features for all supported protocols in H11 are provided by **gigapi** - no other components required!

<br>

### Usage

#### Setup
Clone the repository and launch the **H11** demo using _docker-compose_

```bash
docker-compose pull 
docker-compose up -d
```

#### Send Data
This demo comes with auto-generated data, but you can still send your own using any of the supported methods

##### HEP
Send some HEP traffic to the HEP socket on port 9060/udp or 9061/tcp or use the demo `hepgen` generated traffic

##### Others
Send any data using the `line protocol` format using the GigAPI endpoint on port 7971


#### Login 
Access the preconfigured GigAPI instance
```
http://localhost:7971
```
#### Explore
The demo provides full access to the entire dataset using SQL and the build-in UI

<img width="1919" height="934" alt="image" src="https://github.com/user-attachments/assets/028b414f-d798-4d9a-a012-63bcc9dd7efc" />


#### Data Ingestion
The demo supports _hep_ ingestion and _lineprotocol_ for any other type _(logs, metrics, traces, etc)_

