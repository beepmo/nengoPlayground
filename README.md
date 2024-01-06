Every script is addressing a question!

# NEF/

## `tuning_curve`
Can many neurons, all with the same $J_{\text{thres}}$ and $\alpha$, perfectly recover a 1D input?

YES.

## `2D_tuning_curve`
The tuning curve is a scalar field?
 
 YES.

## `pca_2d`
Can we make a "principal component" visualization of decoders?

YES.

## `hiD_inputs`
Sum tuning curves scalar fields by neuron weights.

=in progress=

## `mnist`
In [image encoding example](https://www.nengo.ai/nengo-extras/examples/mnist_single_layer.html), 28x28 images are 784D vectors?

YES. it works.

# SPA/
## `learning_future`
A `solver` needs to know the signal in the future.
Is it possible to learn a signal that is not known at compile time? In every example shown, including `WhiteSignal`, the learning target can be solved for during the entire duration of simulation.

It sort of makes sense though: you can only train on iid data.

=confused=

## `vtbind`
Hand coded vector-derived transformation binding + comparison with neural simulation.

Are there any neural effects, as in working memory?
 
 NO.

# custom_objects/

## `feedforward_basal-ganglia`
Turn basal ganglia from recurrent network to feedforward by removing GPe. 
=in-progress=

## `dim-change_neuron`
A neuron with input dimensions (tuning curve domain) independent from number of output dimensions (number of custom dendrites)

Probably need to make buffer input (tuning curve gradient  = 0)
=in-progress=

## `sigmoid_tuning_curve`
I thought this could be a custom neuron but it's already a neuron type haha
=complete=


# translations-to-nengo_spa/
How to build a brain tutorials went from `nengo v1.4` to `nengo.spa`. Now `nengo.spa` also became legacy and we have to translate to `nengo_spa`!
