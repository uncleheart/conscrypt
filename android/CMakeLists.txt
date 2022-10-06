cmake_minimum_required(VERSION 3.4.1)
add_library(conscrypt_jni
            SHARED
            ../common/src/jni/main/cpp/conscrypt/compatibility_close_monitor.cc
            ../common/src/jni/main/cpp/conscrypt/jniload.cc
            ../common/src/jni/main/cpp/conscrypt/jniutil.cc
            ../common/src/jni/main/cpp/conscrypt/native_crypto.cc
            ../common/src/jni/main/cpp/conscrypt/netutil.cc

            ../common/src/jni/main/cpp/brotli/common/constants.h
            ../common/src/jni/main/cpp/brotli/common/context.h
            ../common/src/jni/main/cpp/brotli/common/dictionary.c
            ../common/src/jni/main/cpp/brotli/common/dictionary.h
            ../common/src/jni/main/cpp/brotli/common/platform.h
            ../common/src/jni/main/cpp/brotli/common/transform.c
            ../common/src/jni/main/cpp/brotli/common/transform.h
            ../common/src/jni/main/cpp/brotli/common/version.h
            ../common/src/jni/main/cpp/brotli/dec/bit_reader.c
            ../common/src/jni/main/cpp/brotli/dec/bit_reader.h
            ../common/src/jni/main/cpp/brotli/dec/decode.c
            ../common/src/jni/main/cpp/brotli/dec/huffman.c
            ../common/src/jni/main/cpp/brotli/dec/huffman.h
            ../common/src/jni/main/cpp/brotli/dec/prefix.h
            ../common/src/jni/main/cpp/brotli/dec/state.c
            ../common/src/jni/main/cpp/brotli/dec/state.h
            ../common/src/jni/main/cpp/brotli/enc/backward_references.c
            ../common/src/jni/main/cpp/brotli/enc/backward_references.h
            ../common/src/jni/main/cpp/brotli/enc/backward_references_hq.c
            ../common/src/jni/main/cpp/brotli/enc/backward_references_hq.h
            ../common/src/jni/main/cpp/brotli/enc/backward_references_inc.h
            ../common/src/jni/main/cpp/brotli/enc/bit_cost.c
            ../common/src/jni/main/cpp/brotli/enc/bit_cost.h
            ../common/src/jni/main/cpp/brotli/enc/bit_cost_inc.h
            ../common/src/jni/main/cpp/brotli/enc/block_encoder_inc.h
            ../common/src/jni/main/cpp/brotli/enc/block_splitter.c
            ../common/src/jni/main/cpp/brotli/enc/block_splitter.h
            ../common/src/jni/main/cpp/brotli/enc/block_splitter_inc.h
            ../common/src/jni/main/cpp/brotli/enc/brotli_bit_stream.c
            ../common/src/jni/main/cpp/brotli/enc/brotli_bit_stream.h
            ../common/src/jni/main/cpp/brotli/enc/cluster.c
            ../common/src/jni/main/cpp/brotli/enc/cluster.h
            ../common/src/jni/main/cpp/brotli/enc/cluster_inc.h
            ../common/src/jni/main/cpp/brotli/enc/command.h
            ../common/src/jni/main/cpp/brotli/enc/compress_fragment.c
            ../common/src/jni/main/cpp/brotli/enc/compress_fragment.h
            ../common/src/jni/main/cpp/brotli/enc/compress_fragment_two_pass.c
            ../common/src/jni/main/cpp/brotli/enc/compress_fragment_two_pass.h
            ../common/src/jni/main/cpp/brotli/enc/dictionary_hash.c
            ../common/src/jni/main/cpp/brotli/enc/dictionary_hash.h
            ../common/src/jni/main/cpp/brotli/enc/encode.c
            ../common/src/jni/main/cpp/brotli/enc/encoder_dict.c
            ../common/src/jni/main/cpp/brotli/enc/encoder_dict.h
            ../common/src/jni/main/cpp/brotli/enc/entropy_encode.c
            ../common/src/jni/main/cpp/brotli/enc/entropy_encode.h
            ../common/src/jni/main/cpp/brotli/enc/entropy_encode_static.h
            ../common/src/jni/main/cpp/brotli/enc/fast_log.h
            ../common/src/jni/main/cpp/brotli/enc/find_match_length.h
            ../common/src/jni/main/cpp/brotli/enc/hash.h
            ../common/src/jni/main/cpp/brotli/enc/hash_composite_inc.h
            ../common/src/jni/main/cpp/brotli/enc/hash_forgetful_chain_inc.h
            ../common/src/jni/main/cpp/brotli/enc/hash_longest_match64_inc.h
            ../common/src/jni/main/cpp/brotli/enc/hash_longest_match_inc.h
            ../common/src/jni/main/cpp/brotli/enc/hash_longest_match_quickly_inc.h
            ../common/src/jni/main/cpp/brotli/enc/hash_rolling_inc.h
            ../common/src/jni/main/cpp/brotli/enc/hash_to_binary_tree_inc.h
            ../common/src/jni/main/cpp/brotli/enc/histogram.c
            ../common/src/jni/main/cpp/brotli/enc/histogram.h
            ../common/src/jni/main/cpp/brotli/enc/histogram_inc.h
            ../common/src/jni/main/cpp/brotli/enc/literal_cost.c
            ../common/src/jni/main/cpp/brotli/enc/literal_cost.h
            ../common/src/jni/main/cpp/brotli/enc/memory.c
            ../common/src/jni/main/cpp/brotli/enc/memory.h
            ../common/src/jni/main/cpp/brotli/enc/metablock.c
            ../common/src/jni/main/cpp/brotli/enc/metablock.h
            ../common/src/jni/main/cpp/brotli/enc/metablock_inc.h
            ../common/src/jni/main/cpp/brotli/enc/params.h
            ../common/src/jni/main/cpp/brotli/enc/prefix.h
            ../common/src/jni/main/cpp/brotli/enc/quality.h
            ../common/src/jni/main/cpp/brotli/enc/ringbuffer.h
            ../common/src/jni/main/cpp/brotli/enc/static_dict.c
            ../common/src/jni/main/cpp/brotli/enc/static_dict.h
            ../common/src/jni/main/cpp/brotli/enc/static_dict_lut.h
            ../common/src/jni/main/cpp/brotli/enc/utf8_util.c
            ../common/src/jni/main/cpp/brotli/enc/utf8_util.h
            ../common/src/jni/main/cpp/brotli/enc/write_bits.h
            )
include_directories(../common/src/jni/main/include/
                    ../common/src/jni/unbundled/include/
                    ${BORINGSSL_HOME}/include)

find_library(android-log-lib log)
target_link_libraries(conscrypt_jni ${android-log-lib} ssl crypto)

add_definitions(-DANDROID
                -fvisibility=hidden
                -DBORINGSSL_SHARED_LIBRARY
                -DBORINGSSL_IMPLEMENTATION
                -DOPENSSL_SMALL
                -D_XOPEN_SOURCE=700
                -Wno-unused-parameter
                # The following two lines are taken from BoringSSL's build file.  As written there:
                #
                # Clang's -Wtautological-constant-compare is far too aggressive and does not
                # account for, say, wanting the same code to work on both 32-bit and 64-bit
                # platforms.
                #
                # TODO: Remove these when the NDK no longer includes a version that has
                # -Wtautological-constant-compare enabled as part of -Wall
                -Wno-tautological-constant-compare
                -Wtautological-constant-out-of-range-compare)

if (${CMAKE_SYSTEM_PROCESSOR} STREQUAL "aarch64")
    set(CMAKE_ASM_FLAGS "${CMAKE_ASM_FLAGS} -march=armv8-a+crypto")
endif()

add_subdirectory(${BORINGSSL_HOME} ${CMAKE_CURRENT_BINARY_DIR}/boringssl)
