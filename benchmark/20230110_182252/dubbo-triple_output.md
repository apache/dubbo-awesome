# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.978 ops/ms
# Warmup Iteration   2: 2.160 ops/ms
# Warmup Iteration   3: 5.009 ops/ms
Iteration   1: 5.651 ops/ms
Iteration   2: 5.778 ops/ms
Iteration   3: 5.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.779 ±(99.9%) 2.333 ops/ms [Average]
  (min, avg, max) = (5.651, 5.779, 5.907), stdev = 0.128
  CI (99.9%): [3.446, 8.112] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.536 ops/ms
# Warmup Iteration   2: 4.974 ops/ms
# Warmup Iteration   3: 5.725 ops/ms
Iteration   1: 5.993 ops/ms
Iteration   2: 6.152 ops/ms
Iteration   3: 6.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.121 ±(99.9%) 2.095 ops/ms [Average]
  (min, avg, max) = (5.993, 6.121, 6.217), stdev = 0.115
  CI (99.9%): [4.025, 8.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.514 ops/ms
# Warmup Iteration   2: 4.392 ops/ms
# Warmup Iteration   3: 5.502 ops/ms
Iteration   1: 5.656 ops/ms
Iteration   2: 5.660 ops/ms
Iteration   3: 6.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.783 ±(99.9%) 3.945 ops/ms [Average]
  (min, avg, max) = (5.656, 5.783, 6.033), stdev = 0.216
  CI (99.9%): [1.838, 9.727] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.477 ops/ms
# Warmup Iteration   2: 3.859 ops/ms
# Warmup Iteration   3: 4.813 ops/ms
Iteration   1: 4.823 ops/ms
Iteration   2: 5.071 ops/ms
Iteration   3: 5.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.972 ±(99.9%) 2.399 ops/ms [Average]
  (min, avg, max) = (4.823, 4.972, 5.071), stdev = 0.131
  CI (99.9%): [2.573, 7.370] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.304 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 6.996 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.755 ±(99.9%) 0.017 ms/op
Iteration   1: 5.599 ±(99.9%) 0.007 ms/op
Iteration   2: 5.331 ±(99.9%) 0.017 ms/op
Iteration   3: 5.532 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.487 ±(99.9%) 2.547 ms/op [Average]
  (min, avg, max) = (5.331, 5.487, 5.599), stdev = 0.140
  CI (99.9%): [2.941, 8.034] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.914 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.936 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.519 ±(99.9%) 0.012 ms/op
Iteration   1: 5.258 ±(99.9%) 0.005 ms/op
Iteration   2: 5.206 ±(99.9%) 0.008 ms/op
Iteration   3: 5.121 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.195 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (5.121, 5.195, 5.258), stdev = 0.069
  CI (99.9%): [3.931, 6.460] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.748 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.017 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.361 ±(99.9%) 0.010 ms/op
Iteration   1: 5.501 ±(99.9%) 0.015 ms/op
Iteration   2: 5.155 ±(99.9%) 0.012 ms/op
Iteration   3: 5.243 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.300 ±(99.9%) 3.274 ms/op [Average]
  (min, avg, max) = (5.155, 5.300, 5.501), stdev = 0.179
  CI (99.9%): [2.026, 8.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.167 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 7.597 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.584 ±(99.9%) 0.017 ms/op
Iteration   1: 6.504 ±(99.9%) 0.014 ms/op
Iteration   2: 6.175 ±(99.9%) 0.011 ms/op
Iteration   3: 6.425 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.368 ±(99.9%) 3.139 ms/op [Average]
  (min, avg, max) = (6.175, 6.368, 6.504), stdev = 0.172
  CI (99.9%): [3.229, 9.507] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.195 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 8.988 ±(99.9%) 0.075 ms/op
# Warmup Iteration   3: 6.031 ±(99.9%) 0.025 ms/op
Iteration   1: 5.752 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.540 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   7.520 ms/op
                 createUser·p0.95:   9.142 ms/op
                 createUser·p0.99:   11.813 ms/op
                 createUser·p0.999:  22.492 ms/op
                 createUser·p0.9999: 26.604 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   2: 5.963 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   5.562 ms/op
                 createUser·p0.90:   7.635 ms/op
                 createUser·p0.95:   8.585 ms/op
                 createUser·p0.99:   11.403 ms/op
                 createUser·p0.999:  24.731 ms/op
                 createUser·p0.9999: 27.677 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   3: 6.068 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.265 ms/op
                 createUser·p0.50:   5.628 ms/op
                 createUser·p0.90:   8.110 ms/op
                 createUser·p0.95:   9.077 ms/op
                 createUser·p0.99:   11.757 ms/op
                 createUser·p0.999:  17.531 ms/op
                 createUser·p0.9999: 28.680 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 162000
  mean =      5.925 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 41339 
    [ 5.000,  7.500) = 101466 
    [ 7.500, 10.000) = 15120 
    [10.000, 12.500) = 3099 
    [12.500, 15.000) = 577 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.791 ms/op
     p(95.0000) =      8.978 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     27.715 ms/op
     p(99.9990) =     30.020 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 18.159 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 6.823 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.941 ±(99.9%) 0.025 ms/op
Iteration   1: 5.383 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.380 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.717 ms/op
                 existUser·p0.95:   7.922 ms/op
                 existUser·p0.99:   11.092 ms/op
                 existUser·p0.999:  25.121 ms/op
                 existUser·p0.9999: 27.826 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   2: 5.228 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.937 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   7.381 ms/op
                 existUser·p0.99:   10.820 ms/op
                 existUser·p0.999:  25.604 ms/op
                 existUser·p0.9999: 28.788 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   3: 5.203 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.425 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.218 ms/op
                 existUser·p0.95:   7.012 ms/op
                 existUser·p0.99:   9.568 ms/op
                 existUser·p0.999:  27.196 ms/op
                 existUser·p0.9999: 34.911 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182044
  mean =      5.270 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 97171 
    [ 5.000,  7.500) = 75998 
    [ 7.500, 10.000) = 6533 
    [10.000, 12.500) = 1447 
    [12.500, 15.000) = 547 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.937 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.447 ms/op
     p(99.0000) =     10.732 ms/op
     p(99.9000) =     25.492 ms/op
     p(99.9900) =     33.417 ms/op
     p(99.9990) =     35.655 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.931 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 7.314 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.836 ±(99.9%) 0.025 ms/op
Iteration   1: 5.626 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.445 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   7.135 ms/op
                 getUser·p0.95:   8.880 ms/op
                 getUser·p0.99:   12.108 ms/op
                 getUser·p0.999:  18.888 ms/op
                 getUser·p0.9999: 28.606 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   2: 5.538 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.458 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   6.603 ms/op
                 getUser·p0.95:   7.524 ms/op
                 getUser·p0.99:   11.387 ms/op
                 getUser·p0.999:  26.441 ms/op
                 getUser·p0.9999: 30.809 ms/op
                 getUser·p1.00:   31.228 ms/op

Iteration   3: 5.404 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.974 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   6.504 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   9.667 ms/op
                 getUser·p0.999:  30.098 ms/op
                 getUser·p0.9999: 36.379 ms/op
                 getUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173804
  mean =      5.521 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 63072 
    [ 5.000,  7.500) = 100323 
    [ 7.500, 10.000) = 7446 
    [10.000, 12.500) = 1918 
    [12.500, 15.000) = 541 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     37.986 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.861 ±(99.9%) 0.349 ms/op
# Warmup Iteration   2: 8.243 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.916 ±(99.9%) 0.028 ms/op
Iteration   1: 6.681 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   6.234 ms/op
                 listUser·p0.90:   8.086 ms/op
                 listUser·p0.95:   9.880 ms/op
                 listUser·p0.99:   14.123 ms/op
                 listUser·p0.999:  27.730 ms/op
                 listUser·p0.9999: 41.985 ms/op
                 listUser·p1.00:   44.171 ms/op

Iteration   2: 6.499 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.834 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   7.807 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  28.246 ms/op
                 listUser·p0.9999: 32.708 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   3: 6.399 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.927 ms/op
                 listUser·p0.999:  26.542 ms/op
                 listUser·p0.9999: 34.210 ms/op
                 listUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147104
  mean =      6.524 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4089 
    [ 5.000, 10.000) = 137824 
    [10.000, 15.000) = 4498 
    [15.000, 20.000) = 370 
    [20.000, 25.000) = 77 
    [25.000, 30.000) = 161 
    [30.000, 35.000) = 71 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.548 ms/op
     p(50.0000) =      6.160 ms/op
     p(90.0000) =      7.782 ms/op
     p(95.0000) =      9.060 ms/op
     p(99.0000) =     12.763 ms/op
     p(99.9000) =     28.046 ms/op
     p(99.9900) =     34.988 ms/op
     p(99.9990) =     44.110 ms/op
     p(99.9999) =     44.171 ms/op
    p(100.0000) =     44.171 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.779 ± 2.333  ops/ms
ClientPb.existUser                       thrpt       3   6.121 ± 2.095  ops/ms
ClientPb.getUser                         thrpt       3   5.783 ± 3.945  ops/ms
ClientPb.listUser                        thrpt       3   4.972 ± 2.399  ops/ms
ClientPb.createUser                       avgt       3   5.487 ± 2.547   ms/op
ClientPb.existUser                        avgt       3   5.195 ± 1.265   ms/op
ClientPb.getUser                          avgt       3   5.300 ± 3.274   ms/op
ClientPb.listUser                         avgt       3   6.368 ± 3.139   ms/op
ClientPb.createUser                     sample  162000   5.925 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.540           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.791           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.978           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.682           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.857           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.715           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.081           ms/op
ClientPb.existUser                      sample  182044   5.270 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.937           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.956           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.373           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.447           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.732           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.492           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.417           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  173804   5.521 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.974           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.668           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.889           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.141           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.839           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.389           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.470           ms/op
ClientPb.listUser                       sample  147104   6.524 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.160           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.782           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.060           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.763           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.046           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.988           ms/op
ClientPb.listUser:listUser·p1.00        sample          44.171           ms/op
