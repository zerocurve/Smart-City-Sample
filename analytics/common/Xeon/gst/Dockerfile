# smtc_analytics_common_xeon_gst
FROM openvisualcloud/xeon-ubuntu1804-analytics-gst:20.1

RUN DEBIAN_FRONTEND=noninteractive apt-get update -qq && apt-get install -qq python3-gst-1.0 python3-jsonschema && rm -rf /var/lib/apt/lists/*
COPY app /home/
COPY *.py /home/
