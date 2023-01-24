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
# Warmup Iteration   1: 0.915 ops/ms
# Warmup Iteration   2: 2.356 ops/ms
# Warmup Iteration   3: 5.116 ops/ms
Iteration   1: 5.789 ops/ms
Iteration   2: 6.190 ops/ms
Iteration   3: 6.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.055 ±(99.9%) 4.205 ops/ms [Average]
  (min, avg, max) = (5.789, 6.055, 6.190), stdev = 0.231
  CI (99.9%): [1.850, 10.261] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.821 ops/ms
# Warmup Iteration   2: 5.319 ops/ms
# Warmup Iteration   3: 6.514 ops/ms
Iteration   1: 6.658 ops/ms
Iteration   2: 6.631 ops/ms
Iteration   3: 6.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.646 ±(99.9%) 0.253 ops/ms [Average]
  (min, avg, max) = (6.631, 6.646, 6.658), stdev = 0.014
  CI (99.9%): [6.393, 6.899] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.634 ops/ms
# Warmup Iteration   2: 5.119 ops/ms
# Warmup Iteration   3: 6.258 ops/ms
Iteration   1: 6.134 ops/ms
Iteration   2: 6.312 ops/ms
Iteration   3: 6.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.293 ±(99.9%) 2.745 ops/ms [Average]
  (min, avg, max) = (6.134, 6.293, 6.433), stdev = 0.150
  CI (99.9%): [3.548, 9.038] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.598 ops/ms
# Warmup Iteration   2: 4.334 ops/ms
# Warmup Iteration   3: 5.158 ops/ms
Iteration   1: 5.390 ops/ms
Iteration   2: 5.432 ops/ms
Iteration   3: 5.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.339 ±(99.9%) 2.304 ops/ms [Average]
  (min, avg, max) = (5.195, 5.339, 5.432), stdev = 0.126
  CI (99.9%): [3.035, 7.643] (assumes normal distribution)


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
# Warmup Iteration   1: 17.384 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.504 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.350 ±(99.9%) 0.008 ms/op
Iteration   1: 5.011 ±(99.9%) 0.010 ms/op
Iteration   2: 5.167 ±(99.9%) 0.014 ms/op
Iteration   3: 4.944 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.041 ±(99.9%) 2.089 ms/op [Average]
  (min, avg, max) = (4.944, 5.041, 5.167), stdev = 0.114
  CI (99.9%): [2.952, 7.130] (assumes normal distribution)


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
# Warmup Iteration   1: 15.630 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.455 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.958 ±(99.9%) 0.008 ms/op
Iteration   1: 4.613 ±(99.9%) 0.016 ms/op
Iteration   2: 4.862 ±(99.9%) 0.009 ms/op
Iteration   3: 4.819 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.765 ±(99.9%) 2.424 ms/op [Average]
  (min, avg, max) = (4.613, 4.765, 4.862), stdev = 0.133
  CI (99.9%): [2.340, 7.189] (assumes normal distribution)


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
# Warmup Iteration   1: 17.269 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.115 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.197 ±(99.9%) 0.008 ms/op
Iteration   1: 5.192 ±(99.9%) 0.006 ms/op
Iteration   2: 5.257 ±(99.9%) 0.010 ms/op
Iteration   3: 5.029 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.160 ±(99.9%) 2.151 ms/op [Average]
  (min, avg, max) = (5.029, 5.160, 5.257), stdev = 0.118
  CI (99.9%): [3.008, 7.311] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.246 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 7.024 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.973 ±(99.9%) 0.015 ms/op
Iteration   1: 5.824 ±(99.9%) 0.012 ms/op
Iteration   2: 5.570 ±(99.9%) 0.010 ms/op
Iteration   3: 5.906 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.767 ±(99.9%) 3.196 ms/op [Average]
  (min, avg, max) = (5.570, 5.767, 5.906), stdev = 0.175
  CI (99.9%): [2.571, 8.963] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.885 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 7.112 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.472 ±(99.9%) 0.025 ms/op
Iteration   1: 5.269 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.463 ms/op
                 createUser·p0.95:   7.602 ms/op
                 createUser·p0.99:   10.633 ms/op
                 createUser·p0.999:  19.966 ms/op
                 createUser·p0.9999: 24.014 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 4.897 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.327 ms/op
                 createUser·p0.50:   4.661 ms/op
                 createUser·p0.90:   5.800 ms/op
                 createUser·p0.95:   6.545 ms/op
                 createUser·p0.99:   9.273 ms/op
                 createUser·p0.999:  21.114 ms/op
                 createUser·p0.9999: 24.607 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 5.292 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.269 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  25.690 ms/op
                 createUser·p0.9999: 28.344 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 186393
  mean =      5.146 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 110166 
    [ 5.000,  7.500) = 68118 
    [ 7.500, 10.000) = 6149 
    [10.000, 12.500) = 1148 
    [12.500, 15.000) = 462 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      2.212 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     21.548 ms/op
     p(99.9900) =     27.832 ms/op
     p(99.9990) =     28.728 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 15.433 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.399 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.990 ±(99.9%) 0.017 ms/op
Iteration   1: 4.911 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.956 ms/op
                 existUser·p0.50:   4.661 ms/op
                 existUser·p0.90:   5.980 ms/op
                 existUser·p0.95:   6.857 ms/op
                 existUser·p0.99:   9.273 ms/op
                 existUser·p0.999:  21.271 ms/op
                 existUser·p0.9999: 25.510 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   2: 4.891 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.322 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   5.947 ms/op
                 existUser·p0.95:   6.560 ms/op
                 existUser·p0.99:   9.470 ms/op
                 existUser·p0.999:  25.723 ms/op
                 existUser·p0.9999: 29.721 ms/op
                 existUser·p1.00:   33.489 ms/op

Iteration   3: 4.890 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.032 ms/op
                 existUser·p0.50:   4.628 ms/op
                 existUser·p0.90:   5.874 ms/op
                 existUser·p0.95:   6.796 ms/op
                 existUser·p0.99:   9.716 ms/op
                 existUser·p0.999:  16.220 ms/op
                 existUser·p0.9999: 29.441 ms/op
                 existUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 195819
  mean =      4.897 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 138953 
    [ 5.000,  7.500) = 50944 
    [ 7.500, 10.000) = 4377 
    [10.000, 12.500) = 1019 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.956 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     23.900 ms/op
     p(99.9900) =     29.472 ms/op
     p(99.9990) =     33.457 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 16.288 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 5.704 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.279 ±(99.9%) 0.020 ms/op
Iteration   1: 5.134 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.322 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   6.152 ms/op
                 getUser·p0.95:   7.422 ms/op
                 getUser·p0.99:   10.879 ms/op
                 getUser·p0.999:  21.539 ms/op
                 getUser·p0.9999: 25.347 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 5.152 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.331 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.185 ms/op
                 getUser·p0.95:   7.651 ms/op
                 getUser·p0.99:   10.371 ms/op
                 getUser·p0.999:  23.660 ms/op
                 getUser·p0.9999: 27.244 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   3: 4.857 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   4.555 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   6.914 ms/op
                 getUser·p0.99:   9.961 ms/op
                 getUser·p0.999:  20.021 ms/op
                 getUser·p0.9999: 29.560 ms/op
                 getUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 190113
  mean =      5.044 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 123702 
    [ 5.000,  7.500) = 57673 
    [ 7.500, 10.000) = 6387 
    [10.000, 12.500) = 1534 
    [12.500, 15.000) = 490 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.078 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     21.619 ms/op
     p(99.9900) =     29.130 ms/op
     p(99.9990) =     34.079 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 18.410 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 7.483 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.069 ±(99.9%) 0.025 ms/op
Iteration   1: 5.829 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   8.380 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  24.336 ms/op
                 listUser·p0.9999: 26.396 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   2: 5.626 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.450 ms/op
                 listUser·p0.99:   11.238 ms/op
                 listUser·p0.999:  26.829 ms/op
                 listUser·p0.9999: 35.780 ms/op
                 listUser·p1.00:   37.618 ms/op

Iteration   3: 5.868 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 20.093 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 166237
  mean =      5.773 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 28536 
    [ 5.000,  7.500) = 126134 
    [ 7.500, 10.000) = 8287 
    [10.000, 12.500) = 2089 
    [12.500, 15.000) = 601 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      8.135 ms/op
     p(99.0000) =     11.397 ms/op
     p(99.9000) =     22.831 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     36.967 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.055 ± 4.205  ops/ms
ClientPb.existUser                       thrpt       3   6.646 ± 0.253  ops/ms
ClientPb.getUser                         thrpt       3   6.293 ± 2.745  ops/ms
ClientPb.listUser                        thrpt       3   5.339 ± 2.304  ops/ms
ClientPb.createUser                       avgt       3   5.041 ± 2.089   ms/op
ClientPb.existUser                        avgt       3   4.765 ± 2.424   ms/op
ClientPb.getUser                          avgt       3   5.160 ± 2.151   ms/op
ClientPb.listUser                         avgt       3   5.767 ± 3.196   ms/op
ClientPb.createUser                     sample  186393   5.146 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.212           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.825           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.324           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.242           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.109           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.548           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.832           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.295           ms/op
ClientPb.existUser                      sample  195819   4.897 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.956           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.939           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.486           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.900           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.472           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.489           ms/op
ClientPb.getUser                        sample  190113   5.044 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.911           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.332           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.404           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.619           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.130           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  166237   5.773 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.702           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.135           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.397           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.831           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.210           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.618           ms/op
