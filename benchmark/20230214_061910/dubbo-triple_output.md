# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.122 ops/ms
# Warmup Iteration   2: 2.392 ops/ms
# Warmup Iteration   3: 5.335 ops/ms
Iteration   1: 5.627 ops/ms
Iteration   2: 5.962 ops/ms
Iteration   3: 6.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.896 ±(99.9%) 4.432 ops/ms [Average]
  (min, avg, max) = (5.627, 5.896, 6.099), stdev = 0.243
  CI (99.9%): [1.463, 10.328] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.704 ops/ms
# Warmup Iteration   2: 5.448 ops/ms
# Warmup Iteration   3: 6.141 ops/ms
Iteration   1: 6.285 ops/ms
Iteration   2: 6.356 ops/ms
Iteration   3: 6.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.252 ±(99.9%) 2.258 ops/ms [Average]
  (min, avg, max) = (6.115, 6.252, 6.356), stdev = 0.124
  CI (99.9%): [3.994, 8.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.697 ops/ms
# Warmup Iteration   2: 4.862 ops/ms
# Warmup Iteration   3: 5.848 ops/ms
Iteration   1: 6.125 ops/ms
Iteration   2: 6.078 ops/ms
Iteration   3: 6.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.121 ±(99.9%) 0.765 ops/ms [Average]
  (min, avg, max) = (6.078, 6.121, 6.162), stdev = 0.042
  CI (99.9%): [5.357, 6.886] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.708 ops/ms
# Warmup Iteration   2: 4.247 ops/ms
# Warmup Iteration   3: 4.966 ops/ms
Iteration   1: 5.139 ops/ms
Iteration   2: 5.420 ops/ms
Iteration   3: 5.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.395 ±(99.9%) 4.443 ops/ms [Average]
  (min, avg, max) = (5.139, 5.395, 5.624), stdev = 0.244
  CI (99.9%): [0.952, 9.837] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.960 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.534 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.290 ±(99.9%) 0.021 ms/op
Iteration   1: 5.334 ±(99.9%) 0.007 ms/op
Iteration   2: 5.351 ±(99.9%) 0.007 ms/op
Iteration   3: 5.160 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.282 ±(99.9%) 1.925 ms/op [Average]
  (min, avg, max) = (5.160, 5.282, 5.351), stdev = 0.106
  CI (99.9%): [3.357, 7.207] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.204 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 5.931 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.007 ±(99.9%) 0.010 ms/op
Iteration   1: 4.838 ±(99.9%) 0.012 ms/op
Iteration   2: 4.892 ±(99.9%) 0.011 ms/op
Iteration   3: 4.849 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.860 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (4.838, 4.860, 4.892), stdev = 0.028
  CI (99.9%): [4.348, 5.372] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.845 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 7.031 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.373 ±(99.9%) 0.010 ms/op
Iteration   1: 5.214 ±(99.9%) 0.011 ms/op
Iteration   2: 5.344 ±(99.9%) 0.007 ms/op
Iteration   3: 5.223 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.260 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (5.214, 5.260, 5.344), stdev = 0.073
  CI (99.9%): [3.937, 6.584] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.582 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.483 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.129 ±(99.9%) 0.014 ms/op
Iteration   1: 6.192 ±(99.9%) 0.011 ms/op
Iteration   2: 5.958 ±(99.9%) 0.019 ms/op
Iteration   3: 6.027 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.059 ±(99.9%) 2.196 ms/op [Average]
  (min, avg, max) = (5.958, 6.059, 6.192), stdev = 0.120
  CI (99.9%): [3.863, 8.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.739 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 6.992 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.432 ±(99.9%) 0.022 ms/op
Iteration   1: 5.389 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.892 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   6.865 ms/op
                 createUser·p0.95:   7.848 ms/op
                 createUser·p0.99:   10.390 ms/op
                 createUser·p0.999:  24.379 ms/op
                 createUser·p0.9999: 31.489 ms/op
                 createUser·p1.00:   32.211 ms/op

Iteration   2: 5.463 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.776 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.939 ms/op
                 createUser·p0.95:   7.889 ms/op
                 createUser·p0.99:   10.561 ms/op
                 createUser·p0.999:  27.648 ms/op
                 createUser·p0.9999: 32.956 ms/op
                 createUser·p1.00:   36.897 ms/op

Iteration   3: 5.355 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.636 ms/op
                 createUser·p0.95:   7.479 ms/op
                 createUser·p0.99:   10.584 ms/op
                 createUser·p0.999:  26.444 ms/op
                 createUser·p0.9999: 31.757 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177594
  mean =      5.402 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 84262 
    [ 5.000,  7.500) = 82210 
    [ 7.500, 10.000) = 8872 
    [10.000, 12.500) = 1396 
    [12.500, 15.000) = 383 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     25.703 ms/op
     p(99.9900) =     32.079 ms/op
     p(99.9990) =     36.032 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.564 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 5.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.275 ±(99.9%) 0.020 ms/op
Iteration   1: 5.071 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.160 ms/op
                 existUser·p0.95:   7.004 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  24.157 ms/op
                 existUser·p0.9999: 29.121 ms/op
                 existUser·p1.00:   29.360 ms/op

Iteration   2: 5.008 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.150 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   5.972 ms/op
                 existUser·p0.95:   6.783 ms/op
                 existUser·p0.99:   9.306 ms/op
                 existUser·p0.999:  24.651 ms/op
                 existUser·p0.9999: 27.676 ms/op
                 existUser·p1.00:   30.573 ms/op

Iteration   3: 5.138 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.142 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.341 ms/op
                 existUser·p0.95:   7.528 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  31.127 ms/op
                 existUser·p0.9999: 35.000 ms/op
                 existUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 189264
  mean =      5.072 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 118778 
    [ 5.000,  7.500) = 62754 
    [ 7.500, 10.000) = 5769 
    [10.000, 12.500) = 1272 
    [12.500, 15.000) = 407 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.152 ms/op
     p(95.0000) =      7.086 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     24.240 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     35.792 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.562 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 6.168 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.507 ±(99.9%) 0.021 ms/op
Iteration   1: 5.578 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.429 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   7.004 ms/op
                 getUser·p0.95:   8.716 ms/op
                 getUser·p0.99:   14.090 ms/op
                 getUser·p0.999:  26.837 ms/op
                 getUser·p0.9999: 39.518 ms/op
                 getUser·p1.00:   39.649 ms/op

Iteration   2: 5.184 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.429 ms/op
                 getUser·p0.50:   4.907 ms/op
                 getUser·p0.90:   6.275 ms/op
                 getUser·p0.95:   7.086 ms/op
                 getUser·p0.99:   9.634 ms/op
                 getUser·p0.999:  24.987 ms/op
                 getUser·p0.9999: 31.222 ms/op
                 getUser·p1.00:   34.275 ms/op

Iteration   3: 5.358 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.048 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   6.513 ms/op
                 getUser·p0.95:   7.397 ms/op
                 getUser·p0.99:   9.880 ms/op
                 getUser·p0.999:  28.132 ms/op
                 getUser·p0.9999: 33.948 ms/op
                 getUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 178811
  mean =      5.368 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 85929 
    [ 5.000,  7.500) = 82979 
    [ 7.500, 10.000) = 7171 
    [10.000, 12.500) = 1617 
    [12.500, 15.000) = 480 
    [15.000, 17.500) = 210 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.048 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     25.864 ms/op
     p(99.9900) =     38.936 ms/op
     p(99.9990) =     39.649 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.014 ±(99.9%) 0.323 ms/op
# Warmup Iteration   2: 8.064 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.182 ±(99.9%) 0.024 ms/op
Iteration   1: 6.242 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.974 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  29.025 ms/op
                 listUser·p0.9999: 33.908 ms/op
                 listUser·p1.00:   34.996 ms/op

Iteration   2: 6.154 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   7.586 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  29.851 ms/op
                 listUser·p0.9999: 32.296 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   3: 6.046 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   5.702 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  26.085 ms/op
                 listUser·p0.9999: 29.285 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156187
  mean =      6.147 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 14529 
    [ 5.000,  7.500) = 125634 
    [ 7.500, 10.000) = 12148 
    [10.000, 12.500) = 2677 
    [12.500, 15.000) = 618 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.265 ms/op
     p(50.0000) =      5.775 ms/op
     p(90.0000) =      7.537 ms/op
     p(95.0000) =      8.733 ms/op
     p(99.0000) =     11.864 ms/op
     p(99.9000) =     28.103 ms/op
     p(99.9900) =     32.322 ms/op
     p(99.9990) =     34.923 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.896 ± 4.432  ops/ms
ClientPb.existUser                       thrpt       3   6.252 ± 2.258  ops/ms
ClientPb.getUser                         thrpt       3   6.121 ± 0.765  ops/ms
ClientPb.listUser                        thrpt       3   5.395 ± 4.443  ops/ms
ClientPb.createUser                       avgt       3   5.282 ± 1.925   ms/op
ClientPb.existUser                        avgt       3   4.860 ± 0.512   ms/op
ClientPb.getUser                          avgt       3   5.260 ± 1.324   ms/op
ClientPb.listUser                         avgt       3   6.059 ± 2.196   ms/op
ClientPb.createUser                     sample  177594   5.402 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.669           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.808           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.774           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.519           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.703           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.079           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.897           ms/op
ClientPb.existUser                      sample  189264   5.072 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.362           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.776           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.152           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.086           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.093           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.240           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.686           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.962           ms/op
ClientPb.getUser                        sample  178811   5.368 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.048           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.717           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.863           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.864           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.649           ms/op
ClientPb.listUser                       sample  156187   6.147 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.265           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.537           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.864           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.103           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.322           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.996           ms/op
