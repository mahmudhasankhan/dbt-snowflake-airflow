FROM quay.io/astronomer/astro-runtime:9.0.0-python-3.10

# RUN python -m venv dbt_venv && . dbt_venv/bin/activate \
#     pip install --no-cache-dir dbt-snowflake && deactivate
#
# RUN python -m venv dbt_venv && source dbt_venv/bin/activate && pip install --no-cache-dir dbt-snowflake && deactivate

RUN python -m venv dbt_venv && source dbt_venv/bin/activate && \
    pip install --no-cache-dir dbt-snowflake protobuf==4.25.3 && deactivate
