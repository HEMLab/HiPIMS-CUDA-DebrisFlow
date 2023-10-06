{
    "grid_attr": {
        "area": "[185920.0, 'm^2']",
        "shape": "(300, 269)",
        "cellsize": "[2.0, 'm']",
        "num_cells": 46480,
        "extent": {
            "left": 187326.14917362534,
            "right": 187864.14917362534,
            "bottom": 2975284.591703724,
            "top": 2975884.591703724
        }
    },
    "model_attr": {
        "case_folder": "/media/data/lunet/cvxs2/HiPIMS_CUDA_DebrisFlow/DebrisFlowSimulationExample/IO",
        "birthday": "2023-09-12 11:00",
        "num_GPU": 1,
        "run_time": "[0, 86400, 1800, 86400]",
        "num_gauges": 2
    },
    "initial_attr": {
        "h0": 0.0,
        "hU0x": 0,
        "hU0y": 0
    },
    "boundary_attr": {
        "num_boundary": 1,
        "boundary_details": "['0. (outline) fall, h and hU fixed as zero, number of cells: 770']"
    },
    "rain_attr": {
        "num_source": 1,
        "max": "[37.34, 'mm/h']",
        "sum": "[345.64, 'mm']",
        "average": "[14.4, 'mm/h']",
        "spatial_res": "[431.0, 'm']",
        "temporal_res": "[1800.0, 's']"
    },
    "params_attr": {
        "manning": 0.02,
        "sewer_sink": 0,
        "cumulative_depth": 0,
        "hydraulic_conductivity": 0,
        "capillary_head": 0,
        "water_content_diff": 0
    }
}