# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.417 ops/ms
# Warmup Iteration   2: 3.220 ops/ms
# Warmup Iteration   3: 6.021 ops/ms
Iteration   1: 6.111 ops/ms
Iteration   2: 6.660 ops/ms
Iteration   3: 6.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.460 ±(99.9%) 5.536 ops/ms [Average]
  (min, avg, max) = (6.111, 6.460, 6.660), stdev = 0.303
  CI (99.9%): [0.925, 11.996] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.913 ops/ms
# Warmup Iteration   2: 5.952 ops/ms
# Warmup Iteration   3: 6.557 ops/ms
Iteration   1: 7.006 ops/ms
Iteration   2: 6.914 ops/ms
Iteration   3: 7.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.997 ±(99.9%) 1.446 ops/ms [Average]
  (min, avg, max) = (6.914, 6.997, 7.072), stdev = 0.079
  CI (99.9%): [5.551, 8.444] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.048 ops/ms
# Warmup Iteration   2: 5.884 ops/ms
# Warmup Iteration   3: 6.779 ops/ms
Iteration   1: 6.594 ops/ms
Iteration   2: 6.523 ops/ms
Iteration   3: 6.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.633 ±(99.9%) 2.451 ops/ms [Average]
  (min, avg, max) = (6.523, 6.633, 6.783), stdev = 0.134
  CI (99.9%): [4.183, 9.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.804 ops/ms
# Warmup Iteration   2: 4.661 ops/ms
# Warmup Iteration   3: 5.534 ops/ms
Iteration   1: 5.668 ops/ms
Iteration   2: 5.609 ops/ms
Iteration   3: 5.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.666 ±(99.9%) 1.023 ops/ms [Average]
  (min, avg, max) = (5.609, 5.666, 5.721), stdev = 0.056
  CI (99.9%): [4.643, 6.688] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 15.157 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.509 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.224 ±(99.9%) 0.009 ms/op
Iteration   1: 4.820 ±(99.9%) 0.008 ms/op
Iteration   2: 4.917 ±(99.9%) 0.009 ms/op
Iteration   3: 4.822 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.853 ±(99.9%) 1.015 ms/op [Average]
  (min, avg, max) = (4.820, 4.853, 4.917), stdev = 0.056
  CI (99.9%): [3.838, 5.868] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.827 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.389 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.694 ±(99.9%) 0.006 ms/op
Iteration   1: 4.565 ±(99.9%) 0.012 ms/op
Iteration   2: 4.559 ±(99.9%) 0.011 ms/op
Iteration   3: 4.641 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.588 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (4.559, 4.588, 4.641), stdev = 0.046
  CI (99.9%): [3.755, 5.421] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 15.534 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.330 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.773 ±(99.9%) 0.016 ms/op
Iteration   1: 4.821 ±(99.9%) 0.013 ms/op
Iteration   2: 4.951 ±(99.9%) 0.008 ms/op
Iteration   3: 5.018 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.930 ±(99.9%) 1.828 ms/op [Average]
  (min, avg, max) = (4.821, 4.930, 5.018), stdev = 0.100
  CI (99.9%): [3.102, 6.758] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.266 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.987 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.373 ±(99.9%) 0.012 ms/op
Iteration   1: 5.901 ±(99.9%) 0.012 ms/op
Iteration   2: 5.900 ±(99.9%) 0.020 ms/op
Iteration   3: 6.093 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.965 ±(99.9%) 2.030 ms/op [Average]
  (min, avg, max) = (5.900, 5.965, 6.093), stdev = 0.111
  CI (99.9%): [3.935, 7.995] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.641 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 6.290 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.336 ±(99.9%) 0.021 ms/op
Iteration   1: 5.348 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.944 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  22.586 ms/op
                 createUser·p0.9999: 26.183 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 5.264 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.163 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.496 ms/op
                 createUser·p0.95:   7.553 ms/op
                 createUser·p0.99:   10.208 ms/op
                 createUser·p0.999:  24.936 ms/op
                 createUser·p0.9999: 29.292 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 5.142 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.907 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   6.226 ms/op
                 createUser·p0.95:   6.906 ms/op
                 createUser·p0.99:   9.322 ms/op
                 createUser·p0.999:  26.725 ms/op
                 createUser·p0.9999: 30.828 ms/op
                 createUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182712
  mean =      5.250 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 91979 
    [ 5.000,  7.500) = 82541 
    [ 7.500, 10.000) = 6632 
    [10.000, 12.500) = 972 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.907 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     24.038 ms/op
     p(99.9900) =     29.962 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.044 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.805 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.164 ±(99.9%) 0.021 ms/op
Iteration   1: 5.077 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.175 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   6.914 ms/op
                 existUser·p0.99:   9.257 ms/op
                 existUser·p0.999:  20.415 ms/op
                 existUser·p0.9999: 25.310 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   2: 5.133 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.690 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.209 ms/op
                 existUser·p0.99:   9.077 ms/op
                 existUser·p0.999:  21.701 ms/op
                 existUser·p0.9999: 26.960 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 5.037 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   4.768 ms/op
                 existUser·p0.90:   6.210 ms/op
                 existUser·p0.95:   7.238 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  23.914 ms/op
                 existUser·p0.9999: 27.915 ms/op
                 existUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188879
  mean =      5.082 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 114262 
    [ 5.000,  7.500) = 67403 
    [ 7.500, 10.000) = 5691 
    [10.000, 12.500) = 937 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      4.817 ms/op
     p(90.0000) =      6.259 ms/op
     p(95.0000) =      7.135 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     20.492 ms/op
     p(99.9900) =     27.070 ms/op
     p(99.9990) =     31.501 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.412 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.729 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.183 ±(99.9%) 0.018 ms/op
Iteration   1: 5.269 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.454 ms/op
                 getUser·p0.50:   4.891 ms/op
                 getUser·p0.90:   6.423 ms/op
                 getUser·p0.95:   7.946 ms/op
                 getUser·p0.99:   11.649 ms/op
                 getUser·p0.999:  22.522 ms/op
                 getUser·p0.9999: 33.061 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   2: 5.288 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.380 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.995 ms/op
                 getUser·p0.99:   10.720 ms/op
                 getUser·p0.999:  23.315 ms/op
                 getUser·p0.9999: 31.443 ms/op
                 getUser·p1.00:   32.670 ms/op

Iteration   3: 5.089 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.817 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.078 ms/op
                 getUser·p0.95:   6.758 ms/op
                 getUser·p0.99:   9.568 ms/op
                 getUser·p0.999:  24.740 ms/op
                 getUser·p0.9999: 28.073 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183958
  mean =      5.214 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 102003 
    [ 5.000,  7.500) = 72870 
    [ 7.500, 10.000) = 6290 
    [10.000, 12.500) = 2040 
    [12.500, 15.000) = 392 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.817 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.259 ms/op
     p(95.0000) =      7.471 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     22.711 ms/op
     p(99.9900) =     32.408 ms/op
     p(99.9990) =     33.565 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.622 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.719 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.879 ±(99.9%) 0.023 ms/op
Iteration   1: 5.761 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.945 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  24.105 ms/op
                 listUser·p0.9999: 27.179 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   2: 5.661 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   6.603 ms/op
                 listUser·p0.95:   7.332 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  23.119 ms/op
                 listUser·p0.9999: 35.173 ms/op
                 listUser·p1.00:   35.914 ms/op

Iteration   3: 5.923 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.993 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.200 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  17.399 ms/op
                 listUser·p0.9999: 19.713 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 166051
  mean =      5.780 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 27504 
    [ 5.000,  7.500) = 127720 
    [ 7.500, 10.000) = 8474 
    [10.000, 12.500) = 1646 
    [12.500, 15.000) = 319 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      7.938 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     33.567 ms/op
     p(99.9990) =     35.697 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.460 ± 5.536  ops/ms
ClientPb.existUser                       thrpt       3   6.997 ± 1.446  ops/ms
ClientPb.getUser                         thrpt       3   6.633 ± 2.451  ops/ms
ClientPb.listUser                        thrpt       3   5.666 ± 1.023  ops/ms
ClientPb.createUser                       avgt       3   4.853 ± 1.015   ms/op
ClientPb.existUser                        avgt       3   4.588 ± 0.833   ms/op
ClientPb.getUser                          avgt       3   4.930 ± 1.828   ms/op
ClientPb.listUser                         avgt       3   5.965 ± 2.030   ms/op
ClientPb.createUser                     sample  182712   5.250 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.907           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.423           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.307           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.667           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.038           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.962           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.372           ms/op
ClientPb.existUser                      sample  188879   5.082 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.690           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.817           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.259           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.135           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.404           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.492           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.070           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850           ms/op
ClientPb.getUser                        sample  183958   5.214 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.817           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.471           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.715           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.711           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.408           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  166051   5.780 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.462           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.682           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.544           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.567           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.914           ms/op
