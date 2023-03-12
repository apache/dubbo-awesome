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
# Warmup Iteration   1: 1.825 ops/ms
# Warmup Iteration   2: 4.311 ops/ms
# Warmup Iteration   3: 8.300 ops/ms
Iteration   1: 8.692 ops/ms
Iteration   2: 9.106 ops/ms
Iteration   3: 8.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.895 ±(99.9%) 3.779 ops/ms [Average]
  (min, avg, max) = (8.692, 8.895, 9.106), stdev = 0.207
  CI (99.9%): [5.116, 12.674] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.908 ops/ms
# Warmup Iteration   2: 8.305 ops/ms
# Warmup Iteration   3: 9.516 ops/ms
Iteration   1: 9.641 ops/ms
Iteration   2: 9.754 ops/ms
Iteration   3: 9.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.609 ±(99.9%) 2.993 ops/ms [Average]
  (min, avg, max) = (9.431, 9.609, 9.754), stdev = 0.164
  CI (99.9%): [6.615, 12.602] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.744 ops/ms
# Warmup Iteration   2: 8.383 ops/ms
# Warmup Iteration   3: 8.946 ops/ms
Iteration   1: 8.976 ops/ms
Iteration   2: 9.034 ops/ms
Iteration   3: 8.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.976 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (8.917, 8.976, 9.034), stdev = 0.058
  CI (99.9%): [7.909, 10.042] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.394 ops/ms
# Warmup Iteration   2: 6.830 ops/ms
# Warmup Iteration   3: 7.730 ops/ms
Iteration   1: 7.824 ops/ms
Iteration   2: 7.699 ops/ms
Iteration   3: 7.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.829 ±(99.9%) 2.405 ops/ms [Average]
  (min, avg, max) = (7.699, 7.829, 7.963), stdev = 0.132
  CI (99.9%): [5.424, 10.234] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.581 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.004 ms/op
Iteration   1: 3.406 ±(99.9%) 0.008 ms/op
Iteration   2: 3.566 ±(99.9%) 0.009 ms/op
Iteration   3: 3.496 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.489 ±(99.9%) 1.460 ms/op [Average]
  (min, avg, max) = (3.406, 3.489, 3.566), stdev = 0.080
  CI (99.9%): [2.030, 4.949] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.327 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.012 ms/op
Iteration   1: 3.325 ±(99.9%) 0.005 ms/op
Iteration   2: 3.291 ±(99.9%) 0.004 ms/op
Iteration   3: 3.333 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.317 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (3.291, 3.317, 3.333), stdev = 0.022
  CI (99.9%): [2.914, 3.719] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.832 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.004 ms/op
Iteration   1: 3.653 ±(99.9%) 0.003 ms/op
Iteration   2: 3.467 ±(99.9%) 0.008 ms/op
Iteration   3: 3.438 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.519 ±(99.9%) 2.131 ms/op [Average]
  (min, avg, max) = (3.438, 3.519, 3.653), stdev = 0.117
  CI (99.9%): [1.389, 5.650] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.156 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.007 ms/op
Iteration   1: 4.470 ±(99.9%) 0.009 ms/op
Iteration   2: 4.116 ±(99.9%) 0.013 ms/op
Iteration   3: 3.884 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.157 ±(99.9%) 5.379 ms/op [Average]
  (min, avg, max) = (3.884, 4.157, 4.470), stdev = 0.295
  CI (99.9%): [≈ 0, 9.536] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.895 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.011 ms/op
Iteration   1: 3.514 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.123 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  21.986 ms/op
                 createUser·p0.9999: 24.212 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.433 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.741 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  24.278 ms/op
                 createUser·p0.9999: 27.492 ms/op
                 createUser·p1.00:   29.131 ms/op

Iteration   3: 3.430 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  23.321 ms/op
                 createUser·p0.9999: 35.084 ms/op
                 createUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277397
  mean =      3.459 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5002 
    [ 2.500,  5.000) = 265532 
    [ 5.000,  7.500) = 5613 
    [ 7.500, 10.000) = 600 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     22.420 ms/op
     p(99.9900) =     32.531 ms/op
     p(99.9990) =     35.339 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.972 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.009 ms/op
Iteration   1: 3.431 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.614 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.889 ms/op
                 existUser·p0.999:  21.416 ms/op
                 existUser·p0.9999: 25.046 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   2: 3.297 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.306 ms/op
                 existUser·p0.999:  10.942 ms/op
                 existUser·p0.9999: 30.048 ms/op
                 existUser·p1.00:   31.326 ms/op

Iteration   3: 3.396 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.479 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  11.485 ms/op
                 existUser·p0.9999: 29.646 ms/op
                 existUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284435
  mean =      3.374 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10289 
    [ 2.500,  5.000) = 267599 
    [ 5.000,  7.500) = 5490 
    [ 7.500, 10.000) = 647 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     11.757 ms/op
     p(99.9900) =     29.593 ms/op
     p(99.9990) =     30.734 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.072 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.011 ms/op
Iteration   1: 3.586 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  20.316 ms/op
                 getUser·p0.9999: 25.004 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   2: 3.462 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  25.284 ms/op
                 getUser·p0.9999: 27.641 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   3: 3.522 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.954 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  22.666 ms/op
                 getUser·p0.9999: 37.093 ms/op
                 getUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272439
  mean =      3.523 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6524 
    [ 2.500,  5.000) = 257235 
    [ 5.000,  7.500) = 7483 
    [ 7.500, 10.000) = 730 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.012 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     20.730 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     37.297 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.864 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.586 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.016 ms/op
Iteration   1: 4.062 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.852 ms/op
                 listUser·p0.999:  25.863 ms/op
                 listUser·p0.9999: 30.216 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   2: 4.036 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 19.685 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 4.034 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  18.735 ms/op
                 listUser·p0.9999: 23.600 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237204
  mean =      4.044 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 229943 
    [ 5.000,  7.500) = 5216 
    [ 7.500, 10.000) = 1311 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.314 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     18.409 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     31.090 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.895 ± 3.779  ops/ms
ClientPb.existUser                       thrpt       3   9.609 ± 2.993  ops/ms
ClientPb.getUser                         thrpt       3   8.976 ± 1.066  ops/ms
ClientPb.listUser                        thrpt       3   7.829 ± 2.405  ops/ms
ClientPb.createUser                       avgt       3   3.489 ± 1.460   ms/op
ClientPb.existUser                        avgt       3   3.317 ± 0.403   ms/op
ClientPb.getUser                          avgt       3   3.519 ± 2.131   ms/op
ClientPb.listUser                         avgt       3   4.157 ± 5.379   ms/op
ClientPb.createUser                     sample  277397   3.459 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.315           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.420           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.531           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.717           ms/op
ClientPb.existUser                      sample  284435   3.374 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.458           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.757           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.593           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.326           ms/op
ClientPb.getUser                        sample  272439   3.523 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.012           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.439           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.730           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.389           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.945           ms/op
ClientPb.listUser                       sample  237204   4.044 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.314           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.127           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.409           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.360           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.326           ms/op
