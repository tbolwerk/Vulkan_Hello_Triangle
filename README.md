# Vulkan_Hello_Triangle


## Setup
 
 brew install vulkan-sdk glsf

 export VULKAN_ROOT_LOCATION="/usr/local/Caskroom/vulkan-sdk/$VULKAN_SDK_VERSION"

 export VULKAN_SDK="$VULKAN_ROOT_LOCATION/macOS"

 export PATH="$PATH:$VULKAN_SDK/bi"

 export DYLD_LIBRARY_PATH="$VULKAN_SDK/lib:$DYLD_LIBRARY_PATH"

 export VK_ICD_FILENAMES=$VULKAN_SDK/share/vulkan/icd.d/MoltenVK_icd.json 

 export VK_LAYER_PATH=$VULKAN_SDK/share/vulkan/explicit_layer.d

## Run

cmake ..

make

./vulkanHelloWorld