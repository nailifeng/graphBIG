ROOT=../..
TARGET=graphconstruct
OBJS=graphconstruct.o

RUN_ARGS=--vertex 1000  --edge 10000
PERF_ARGS=--perf-event PERF_COUNT_HW_CPU_CYCLES PERF_COUNT_HW_INSTRUCTIONS PERF_COUNT_HW_BRANCH_INSTRUCTIONS PERF_COUNT_HW_BRANCH_MISSES PERF_COUNT_HW_CACHE_L1D_READ_ACCESS PERF_COUNT_HW_CACHE_L1D_READ_MISS 
#LINKER_OPTIONS+=-static
EXTRA_CXX_FLAGS+=-fopenmp
include ../common.mk


