ADD_LIBRARY(PetaverseHC
    petaverse-hillclimber
    interactive-hillclimber
    HCPetaverseVocabularyProvider
)

TARGET_LINK_LIBRARIES(PetaverseHC
    RewritingRules
    comboreduct
    ${COGUTIL_LIBRARY}
    FitnessEstimator
    AvatarComboVocabulary
)
