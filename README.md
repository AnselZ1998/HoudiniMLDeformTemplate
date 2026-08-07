# ML Deform Template

A simple Houdini template for preparing training data for ML Deformer workflows.

## Contents

- `MLDeformTemplate.hip` — Houdini template for pose generation, joint limits, simulation, and target data preparation.

## Workflow

1. Set the global parameters such as pose count and PCA dimensions.
2. Prepare the character assets and skeleton.
3. Add animation if needed.
4. Configure joint limits.
5. Run your custom simulation.
6. Output the solved skinned pose as the training target.

## Notes

The simulation pipeline can be customized depending on the project.  
Only the final solved skinned pose is required as the target.

## Future Updates

More tools and code for batch processing and render-farm / farm workflows will be added in future updates.

## Requirements

- SideFX Houdini

