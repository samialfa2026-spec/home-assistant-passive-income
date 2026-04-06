ARG BUILD_FROM
FROM ${BUILD_FROM}

ENV token ""
ENV device_name ""

ENTRYPOINT ./Cli "start" "accept" "--token" "$token" "--device-name" "$device_name"
