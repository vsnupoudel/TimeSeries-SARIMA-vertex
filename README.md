# TimeSeries-vertex
```
{
  "targetColumn": "Close_Price",
  "timeSeriesIdentifierColumn": "Week_Number",
  "timeColumn": "Close_Time",
  "optimizationObjective": "minimize-rmse",
  "trainBudgetMilliNodeHours": "2000",
  "unavailableAtForecastColumns": [
    "Close_Price"
  ],
  "availableAtForecastColumns": [
    "Close_Time"
  ],
  "dataGranularity": {
    "unit": "minute",
    "quantity": "5"
  },
  "forecastHorizon": "30",
  "contextWindow": "120",
  "windowConfig": {
    "strideLength": "6"
  },
  "modelDisplayName": "bitcoin_02_05"
}
```

- resource.type="cloudml_job" resource.labels.job_id="5125866034087067648" resource.labels.project_id="starry-embassy-363916" labels.log_type="automl_forecasting" jsonPayload."@type"="type.googleapis.com/google.cloud.automl.master.TablesModelStructure"

```
{
  "insertId": "l3jxy4f6ozg41",
  "jsonPayload": {
    "modelParameters": [
      {
        "hyperparameters": {
          "seq_q2h_attn_size": 256,
          "model_type": "forecasting_l2l",
          "pos_type": "emb",
          "enable_l1": false,
          "use_output_gate": true,
          "num_cross_layers": 3,
          "seq_hidden_size": 32,
          "enable_batch_norm": false,
          "num_hidden_layers": 1,
          "hidden_layer_size_01": 32,
          "use_future_seq": true,
          "use_causal_on_history": false,
          "enable_layer_norm": true,
          "use_causal_on_future": false,
          "seq_dropout": 0.25,
          "numerical_embedding_dimension": 16,
          "enable_embedding_l1": true,
          "skip_connections_type": "concat",
          "respect_time_mask": true,
          "seq_q2h_attn_num_heads": 16,
          "dropout": 0.25,
          "enable_numerical_embeddings": true,
          "enable_l2": true,
          "normalized_numerical": true,
          "seq_use_batch_norm": false,
          "use_separate_output_heads": false,
          "seq_num_layers": 1,
          "sequence_model_type": "lstm",
          "use_aggregated_features": false,
          "hidden_layer_size_0": 512,
          "enable_embedding_l2": false
        }
      },
      {
        "hyperparameters": {
          "respect_time_mask": true,
          "seq_q2h_attn_size": 256,
          "use_causal_on_history": false,
          "hidden_layer_size_0": 512,
          "enable_layer_norm": true,
          "enable_embedding_l2": false,
          "pos_type": "emb",
          "num_hidden_layers": 1,
          "seq_use_batch_norm": false,
          "numerical_embedding_dimension": 16,
          "sequence_model_type": "lstm",
          "use_future_seq": true,
          "use_output_gate": true,
          "seq_num_layers": 1,
          "use_aggregated_features": false,
          "use_separate_output_heads": false,
          "dropout": 0.5,
          "enable_batch_norm": false,
          "enable_l2": true,
          "seq_q2h_attn_num_heads": 16,
          "use_causal_on_future": false,
          "enable_l1": false,
          "normalized_numerical": true,
          "seq_hidden_size": 32,
          "num_cross_layers": 4,
          "skip_connections_type": "concat",
          "enable_embedding_l1": true,
          "seq_dropout": 0,
          "hidden_layer_size_01": 32,
          "model_type": "forecasting_l2l",
          "enable_numerical_embeddings": true
        }
      },
      {
        "hyperparameters": {
          "enable_batch_norm": false,
          "enable_embedding_l2": false,
          "skip_connections_type": "concat",
          "enable_embedding_l1": true,
          "use_separate_output_heads": false,
          "hidden_layer_size_01": 32,
          "model_type": "forecasting_l2l",
          "respect_time_mask": true,
          "enable_numerical_embeddings": true,
          "use_future_seq": true,
          "enable_l2": true,
          "dropout": 0.25,
          "seq_dropout": 0.5,
          "normalized_numerical": true,
          "hidden_layer_size_0": 256,
          "use_causal_on_future": false,
          "seq_hidden_size": 64,
          "seq_q2h_attn_num_heads": 16,
          "use_aggregated_features": false,
          "sequence_model_type": "lstm",
          "seq_use_batch_norm": false,
          "num_hidden_layers": 1,
          "enable_l1": false,
          "seq_num_layers": 1,
          "seq_q2h_attn_size": 128,
          "numerical_embedding_dimension": 16,
          "num_cross_layers": 1,
          "pos_type": "emb",
          "enable_layer_norm": true,
          "use_causal_on_history": false,
          "use_output_gate": true
        }
      },
      {
        "hyperparameters": {
          "enable_numerical_embeddings": true,
          "normalized_numerical": true,
          "seq_q2h_attn_num_heads": 8,
          "seq_num_layers": 2,
          "use_future_seq": true,
          "enable_layer_norm": true,
          "model_type": "forecasting_l2l",
          "num_cross_layers": 2,
          "enable_l1": false,
          "use_output_gate": false,
          "use_separate_output_heads": false,
          "num_hidden_layers": 1,
          "seq_use_batch_norm": true,
          "use_aggregated_features": false,
          "hidden_layer_size_01": 32,
          "sequence_model_type": "lstm",
          "use_causal_on_history": false,
          "dropout": 0,
          "seq_dropout": 0.5,
          "skip_connections_type": "concat",
          "pos_type": "emb",
          "seq_q2h_attn_size": 256,
          "seq_hidden_size": 64,
          "numerical_embedding_dimension": 16,
          "enable_embedding_l2": false,
          "enable_l2": false,
          "use_causal_on_future": false,
          "hidden_layer_size_0": 256,
          "enable_embedding_l1": true,
          "respect_time_mask": true,
          "enable_batch_norm": false
        }
      },
      {
        "hyperparameters": {
          "use_output_gate": true,
          "numerical_embedding_dimension": 64,
          "seq_num_layers": 2,
          "num_hidden_layers": 1,
          "seq_dropout": 0,
          "model_type": "forecasting_l2l",
          "enable_l1": false,
          "seq_hidden_size": 32,
          "respect_time_mask": true,
          "skip_connections_type": "concat",
          "enable_layer_norm": true,
          "pos_type": "emb",
          "seq_q2h_attn_num_heads": 8,
          "num_cross_layers": 4,
          "normalized_numerical": true,
          "enable_numerical_embeddings": true,
          "use_causal_on_history": false,
          "use_causal_on_future": false,
          "enable_embedding_l2": false,
          "enable_embedding_l1": true,
          "enable_l2": true,
          "dropout": 0.25,
          "hidden_layer_size_01": 32,
          "enable_batch_norm": false,
          "hidden_layer_size_0": 256,
          "use_aggregated_features": false,
          "seq_use_batch_norm": false,
          "seq_q2h_attn_size": 128,
          "use_future_seq": true,
          "use_separate_output_heads": false,
          "sequence_model_type": "lstm"
        }
      },
      {
        "hyperparameters": {
          "num_hidden_layers": 1,
          "enable_layer_norm": true,
          "enable_numerical_embeddings": true,
          "use_separate_output_heads": false,
          "use_future_seq": true,
          "hidden_layer_size_0": 256,
          "hidden_layer_size_01": 32,
          "skip_connections_type": "concat",
          "enable_l2": true,
          "seq_hidden_size": 32,
          "model_type": "forecasting_l2l",
          "use_output_gate": true,
          "seq_q2h_attn_num_heads": 8,
          "respect_time_mask": true,
          "seq_use_batch_norm": false,
          "normalized_numerical": true,
          "seq_num_layers": 2,
          "sequence_model_type": "lstm",
          "enable_embedding_l1": true,
          "pos_type": "emb",
          "numerical_embedding_dimension": 64,
          "use_causal_on_history": false,
          "enable_embedding_l2": false,
          "seq_dropout": 0,
          "dropout": 0,
          "seq_q2h_attn_size": 128,
          "enable_l1": false,
          "enable_batch_norm": false,
          "num_cross_layers": 4,
          "use_aggregated_features": false,
          "use_causal_on_future": false
        }
      },
      {
        "hyperparameters": {
          "num_hidden_layers": 1,
          "use_causal_on_history": false,
          "seq_num_layers": 2,
          "enable_l1": false,
          "hidden_layer_size_0": 256,
          "sequence_model_type": "lstm",
          "seq_use_batch_norm": false,
          "use_causal_on_future": false,
          "enable_l2": true,
          "dropout": 0,
          "seq_q2h_attn_size": 128,
          "enable_layer_norm": true,
          "enable_batch_norm": false,
          "use_future_seq": true,
          "model_type": "forecasting_l2l",
          "normalized_numerical": true,
          "num_cross_layers": 2,
          "enable_numerical_embeddings": true,
          "skip_connections_type": "concat",
          "pos_type": "emb",
          "use_separate_output_heads": false,
          "seq_dropout": 0.5,
          "respect_time_mask": true,
          "numerical_embedding_dimension": 64,
          "use_output_gate": true,
          "seq_q2h_attn_num_heads": 16,
          "enable_embedding_l1": true,
          "seq_hidden_size": 32,
          "use_aggregated_features": false,
          "hidden_layer_size_01": 32,
          "enable_embedding_l2": false
        }
      },
      {
        "hyperparameters": {
          "hidden_layer_size_0": 512,
          "seq_dropout": 0.25,
          "sequence_model_type": "lstm",
          "num_cross_layers": 2,
          "pos_type": "timing",
          "enable_l2": false,
          "use_future_seq": true,
          "respect_time_mask": true,
          "enable_embedding_l2": true,
          "enable_embedding_l1": true,
          "enable_batch_norm": false,
          "use_aggregated_features": false,
          "seq_q2h_attn_size": 128,
          "numerical_embedding_dimension": 64,
          "use_output_gate": false,
          "enable_numerical_embeddings": true,
          "dropout": 0.25,
          "use_causal_on_history": false,
          "seq_q2h_attn_num_heads": 8,
          "seq_hidden_size": 32,
          "normalized_numerical": true,
          "enable_l1": false,
          "model_type": "forecasting_l2l",
          "use_causal_on_future": false,
          "enable_layer_norm": true,
          "num_hidden_layers": 2,
          "hidden_layer_size_01": 32,
          "seq_use_batch_norm": false,
          "seq_num_layers": 1,
          "skip_connections_type": "dense",
          "use_separate_output_heads": false
        }
      },
      {
        "hyperparameters": {
          "use_output_gate": true,
          "seq_q2h_attn_size": 128,
          "enable_embedding_l1": true,
          "seq_hidden_size": 64,
          "seq_use_batch_norm": true,
          "dropout": 0,
          "use_future_seq": true,
          "pos_type": "emb",
          "normalized_numerical": true,
          "seq_dropout": 0.5,
          "num_hidden_layers": 1,
          "hidden_layer_size_01": 32,
          "enable_layer_norm": true,
          "enable_embedding_l2": false,
          "sequence_model_type": "lstm",
          "use_causal_on_history": false,
          "enable_batch_norm": false,
          "numerical_embedding_dimension": 16,
          "use_separate_output_heads": false,
          "seq_num_layers": 1,
          "respect_time_mask": true,
          "skip_connections_type": "concat",
          "use_aggregated_features": false,
          "enable_l2": true,
          "model_type": "forecasting_l2l",
          "seq_q2h_attn_num_heads": 8,
          "enable_numerical_embeddings": true,
          "enable_l1": false,
          "num_cross_layers": 4,
          "use_causal_on_future": false,
          "hidden_layer_size_0": 256
        }
      },
      {
        "hyperparameters": {
          "seq_q2h_attn_num_heads": 8,
          "seq_hidden_size": 64,
          "dropout": 0.5,
          "enable_numerical_embeddings": true,
          "hidden_layer_size_0": 512,
          "enable_l2": false,
          "use_causal_on_history": false,
          "seq_num_layers": 1,
          "hidden_layer_size_01": 32,
          "normalized_numerical": true,
          "num_hidden_layers": 1,
          "pos_type": "emb",
          "seq_dropout": 0.25,
          "sequence_model_type": "lstm",
          "use_aggregated_features": false,
          "skip_connections_type": "concat",
          "enable_batch_norm": false,
          "use_output_gate": true,
          "numerical_embedding_dimension": 16,
          "use_future_seq": true,
          "model_type": "forecasting_l2l",
          "enable_layer_norm": true,
          "enable_embedding_l2": false,
          "enable_l1": false,
          "enable_embedding_l1": true,
          "seq_q2h_attn_size": 256,
          "use_separate_output_heads": false,
          "use_causal_on_future": false,
          "seq_use_batch_norm": false,
          "num_cross_layers": 2,
          "respect_time_mask": true
        }
      }
    ],
    "@type": "type.googleapis.com/google.cloud.automl.master.TablesModelStructure"
  },
  "resource": {
    "type": "cloudml_job",
    "labels": {
      "job_id": "5125866034087067648",
      "region": "us-central1",
      "project_id": "starry-embassy-363916"
    }
  },
  "timestamp": "2022-10-30T10:21:19.399990Z",
  "severity": "INFO",
  "labels": {
    "log_type": "automl_forecasting"
  },
  "logName": "projects/starry-embassy-363916/logs/automl.googleapis.com%2Fmodel",
  "receiveTimestamp": "2022-10-30T13:02:13.952952273Z"
}
```

- resource.type="cloudml_job" resource.labels.job_id="5125866034087067648" resource.labels.project_id="starry-embassy-363916" labels.log_type="automl_forecasting" jsonPayload."@type"="type.googleapis.com/google.cloud.automl.master.TuningTrial"

```
{
  "insertId": "1ixxjoqf61i9qy",
  "jsonPayload": {
    "modelStructure": {
      "modelParameters": [
        {
          "hyperparameters": {
            "use_aggregated_features": "False",
            "enable_embedding_l1": "False",
            "use_causal_on_future": "False",
            "seq_hidden_size": 64,
            "num_cross_layers": 2,
            "seq_use_batch_norm": "True",
            "seq_q2h_attn_num_heads": 16,
            "use_causal_on_history": "False",
            "pos_type": "timing",
            "enable_embedding_l2": "True",
            "hidden_layer_size_0": 512,
            "enable_batch_norm": "False",
            "normalized_numerical": "True",
            "use_output_gate": "True",
            "enable_l2": "False",
            "seq_num_layers": 2,
            "model_type": "forecasting_l2l",
            "num_hidden_layers": 2,
            "sequence_model_type": "lstm",
            "enable_l1": "True",
            "dropout": 0.25,
            "enable_numerical_embeddings": "True",
            "seq_dropout": 0.25,
            "respect_time_mask": "True",
            "seq_q2h_attn_size": 256,
            "numerical_embedding_dimension": 64,
            "enable_layer_norm": "True",
            "hidden_layer_size_01": 64,
            "use_future_seq": "True",
            "skip_connections_type": "slice_or_padding",
            "use_separate_output_heads": "False"
          }
        }
      ]
    },
    "trainingObjectivePoint": {
      "value": 1973.0432,
      "createTime": "2022-10-30T11:18:12Z"
    },
    "@type": "type.googleapis.com/google.cloud.automl.master.TuningTrial"
  },
  "resource": {
    "type": "cloudml_job",
    "labels": {
      "region": "us-central1",
      "project_id": "starry-embassy-363916",
      "job_id": "5125866034087067648"
    }
  },
  "timestamp": "2022-10-30T10:21:19.399990Z",
  "severity": "INFO",
  "labels": {
    "log_type": "automl_forecasting"
  },
  "logName": "projects/starry-embassy-363916/logs/automl.googleapis.com%2Ftuning",
  "receiveTimestamp": "2022-10-30T13:02:13.957864578Z"
}
```
