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
# Warmup Iteration   1: 2.362 ops/ms
# Warmup Iteration   2: 5.824 ops/ms
# Warmup Iteration   3: 8.683 ops/ms
Iteration   1: 9.277 ops/ms
Iteration   2: 9.092 ops/ms
Iteration   3: 9.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.290 ±(99.9%) 3.758 ops/ms [Average]
  (min, avg, max) = (9.092, 9.290, 9.503), stdev = 0.206
  CI (99.9%): [5.532, 13.049] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.022 ops/ms
# Warmup Iteration   2: 8.892 ops/ms
# Warmup Iteration   3: 9.492 ops/ms
Iteration   1: 9.541 ops/ms
Iteration   2: 9.864 ops/ms
Iteration   3: 10.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.809 ±(99.9%) 4.462 ops/ms [Average]
  (min, avg, max) = (9.541, 9.809, 10.021), stdev = 0.245
  CI (99.9%): [5.347, 14.271] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.312 ops/ms
# Warmup Iteration   2: 8.501 ops/ms
# Warmup Iteration   3: 8.904 ops/ms
Iteration   1: 9.632 ops/ms
Iteration   2: 9.286 ops/ms
Iteration   3: 9.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.433 ±(99.9%) 3.260 ops/ms [Average]
  (min, avg, max) = (9.286, 9.433, 9.632), stdev = 0.179
  CI (99.9%): [6.173, 12.693] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.886 ops/ms
# Warmup Iteration   2: 7.434 ops/ms
# Warmup Iteration   3: 7.781 ops/ms
Iteration   1: 7.917 ops/ms
Iteration   2: 7.985 ops/ms
Iteration   3: 8.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.020 ±(99.9%) 2.272 ops/ms [Average]
  (min, avg, max) = (7.917, 8.020, 8.158), stdev = 0.125
  CI (99.9%): [5.748, 10.292] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.064 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.004 ms/op
Iteration   1: 3.450 ±(99.9%) 0.010 ms/op
Iteration   2: 3.414 ±(99.9%) 0.007 ms/op
Iteration   3: 3.440 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.435 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.414, 3.435, 3.450), stdev = 0.019
  CI (99.9%): [3.097, 3.773] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.321 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.006 ms/op
Iteration   1: 3.325 ±(99.9%) 0.006 ms/op
Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
Iteration   3: 3.356 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.321 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.282, 3.321, 3.356), stdev = 0.037
  CI (99.9%): [2.642, 4.000] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.107 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.011 ms/op
Iteration   1: 3.355 ±(99.9%) 0.011 ms/op
Iteration   2: 3.350 ±(99.9%) 0.009 ms/op
Iteration   3: 3.328 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.344 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (3.328, 3.344, 3.355), stdev = 0.014
  CI (99.9%): [3.084, 3.604] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.868 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.014 ms/op
Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
Iteration   2: 3.932 ±(99.9%) 0.010 ms/op
Iteration   3: 3.918 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.939 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.918, 3.939, 3.967), stdev = 0.025
  CI (99.9%): [3.487, 4.391] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.249 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.008 ms/op
Iteration   1: 3.593 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   6.972 ms/op
                 createUser·p0.999:  19.857 ms/op
                 createUser·p0.9999: 24.413 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   2: 3.583 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.551 ms/op
                 createUser·p0.999:  17.924 ms/op
                 createUser·p0.9999: 28.775 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 3.444 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  21.763 ms/op
                 createUser·p0.9999: 28.574 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271066
  mean =      3.538 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5814 
    [ 2.500,  5.000) = 252461 
    [ 5.000,  7.500) = 11363 
    [ 7.500, 10.000) = 847 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     19.298 ms/op
     p(99.9900) =     28.272 ms/op
     p(99.9990) =     29.506 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.849 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.007 ms/op
Iteration   1: 3.312 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  17.134 ms/op
                 existUser·p0.9999: 24.067 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   2: 3.225 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.258 ms/op
                 existUser·p0.999:  17.294 ms/op
                 existUser·p0.9999: 23.409 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   3: 3.294 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  11.394 ms/op
                 existUser·p0.9999: 24.376 ms/op
                 existUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292758
  mean =      3.277 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9727 
    [ 2.500,  5.000) = 278324 
    [ 5.000,  7.500) = 3692 
    [ 7.500, 10.000) = 474 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     15.192 ms/op
     p(99.9900) =     23.682 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.730 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.011 ms/op
Iteration   1: 3.458 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  18.993 ms/op
                 getUser·p0.9999: 46.888 ms/op
                 getUser·p1.00:   55.837 ms/op

Iteration   2: 3.520 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.538 ms/op
                 getUser·p0.999:  21.332 ms/op
                 getUser·p0.9999: 25.297 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   3: 3.400 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  20.312 ms/op
                 getUser·p0.9999: 26.586 ms/op
                 getUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277793
  mean =      3.459 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 270144 
    [ 5.000, 10.000) = 7247 
    [10.000, 15.000) = 114 
    [15.000, 20.000) = 20 
    [20.000, 25.000) = 190 
    [25.000, 30.000) = 47 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 21 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.155 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     19.248 ms/op
     p(99.9900) =     44.921 ms/op
     p(99.9990) =     55.837 ms/op
     p(99.9999) =     55.837 ms/op
    p(100.0000) =     55.837 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.021 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.014 ms/op
Iteration   1: 4.023 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  21.168 ms/op
                 listUser·p0.9999: 29.267 ms/op
                 listUser·p1.00:   30.507 ms/op

Iteration   2: 3.875 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 16.328 ms/op
                 listUser·p1.00:   16.482 ms/op

Iteration   3: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.562 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 20.968 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243165
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 235300 
    [ 5.000,  7.500) = 5839 
    [ 7.500, 10.000) = 1291 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     27.285 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.290 ± 3.758  ops/ms
ClientPb.existUser                       thrpt       3   9.809 ± 4.462  ops/ms
ClientPb.getUser                         thrpt       3   9.433 ± 3.260  ops/ms
ClientPb.listUser                        thrpt       3   8.020 ± 2.272  ops/ms
ClientPb.createUser                       avgt       3   3.435 ± 0.338   ms/op
ClientPb.existUser                        avgt       3   3.321 ± 0.679   ms/op
ClientPb.getUser                          avgt       3   3.344 ± 0.260   ms/op
ClientPb.listUser                         avgt       3   3.939 ± 0.452   ms/op
ClientPb.createUser                     sample  271066   3.538 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.092           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.783           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.298           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.272           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.983           ms/op
ClientPb.existUser                      sample  292758   3.277 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.192           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.682           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.657           ms/op
ClientPb.getUser                        sample  277793   3.459 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.100           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.155           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.248           ms/op
ClientPb.getUser:getUser·p0.9999        sample          44.921           ms/op
ClientPb.getUser:getUser·p1.00          sample          55.837           ms/op
ClientPb.listUser                       sample  243165   3.946 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.448           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.516           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.285           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.507           ms/op
