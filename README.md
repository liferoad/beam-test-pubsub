
# Simple Test

## Run with DirectRunner

```bash
python main.py --project=<your_gcp_project>
```

## Run with DataflowRunner

```bash
python main.py --project=<your_gcp_project> --runner=DataflowRunner --region=us-east1 --temp_location=<gs_bucket> --staging_location=<gs_bucket> --requirements_file=requirements.txt
```
