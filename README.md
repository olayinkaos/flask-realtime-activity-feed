# Flask Realtime Activity Feed
Realtime activity feed built with Python and Pusher. You can follow the tutorial for it on the [Pusher Blog](https://blog.pusher.com/build-realtime-activity-feed-flask-pusher/).

To run locally:
- Clone/Download this repo - `git clone https://github.com/olayinkaos/flask-realtime-activity-feed.git`
- [Optionally] Create a local virtualenv in the project folder (You must have virtualenv installed) - `virtualenv .venv`
- [Optionally] Activate virtual environment - `source .venv/bin/activate`
- Install all dependencies - `pip install -r requirements.txt`
- Replace the values of  `YOUR_APP_ID`, `YOUR_APP_KEY`, `YOUR_APP_SECRET`, `YOUR_APP_CLUSTER` with your Pusher credentials in `app.py`, `index.html` and `feed.html`. These can be gotten from the [Pusher dashboard](https://dashboard.pusher.com/).
- Run app - `python app.py`
- Visit [localhost:5000](http://localhost:5000/) to view the app.
