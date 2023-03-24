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
# Warmup Iteration   1: 1.678 ops/ms
# Warmup Iteration   2: 3.543 ops/ms
# Warmup Iteration   3: 7.523 ops/ms
Iteration   1: 7.729 ops/ms
Iteration   2: 8.429 ops/ms
Iteration   3: 8.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.098 ±(99.9%) 6.411 ops/ms [Average]
  (min, avg, max) = (7.729, 8.098, 8.429), stdev = 0.351
  CI (99.9%): [1.687, 14.510] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.459 ops/ms
# Warmup Iteration   2: 7.369 ops/ms
# Warmup Iteration   3: 8.680 ops/ms
Iteration   1: 8.485 ops/ms
Iteration   2: 8.545 ops/ms
Iteration   3: 8.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.551 ±(99.9%) 1.275 ops/ms [Average]
  (min, avg, max) = (8.485, 8.551, 8.624), stdev = 0.070
  CI (99.9%): [7.277, 9.826] (assumes normal distribution)


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
# Warmup Iteration   1: 2.348 ops/ms
# Warmup Iteration   2: 6.766 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 8.037 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.238 ±(99.9%) 3.457 ops/ms [Average]
  (min, avg, max) = (8.037, 8.238, 8.413), stdev = 0.189
  CI (99.9%): [4.781, 11.695] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.423 ops/ms
# Warmup Iteration   2: 6.053 ops/ms
# Warmup Iteration   3: 6.883 ops/ms
Iteration   1: 6.814 ops/ms
Iteration   2: 6.766 ops/ms
Iteration   3: 7.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.881 ±(99.9%) 2.916 ops/ms [Average]
  (min, avg, max) = (6.766, 6.881, 7.064), stdev = 0.160
  CI (99.9%): [3.965, 9.797] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.644 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.004 ms/op
Iteration   1: 3.858 ±(99.9%) 0.009 ms/op
Iteration   2: 3.836 ±(99.9%) 0.009 ms/op
Iteration   3: 3.806 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.833 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (3.806, 3.833, 3.858), stdev = 0.026
  CI (99.9%): [3.353, 4.314] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.541 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.007 ms/op
Iteration   1: 3.695 ±(99.9%) 0.008 ms/op
Iteration   2: 3.705 ±(99.9%) 0.004 ms/op
Iteration   3: 3.775 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.725 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (3.695, 3.725, 3.775), stdev = 0.043
  CI (99.9%): [2.934, 4.515] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.472 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.025 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.902 ±(99.9%) 0.005 ms/op
Iteration   2: 3.870 ±(99.9%) 0.005 ms/op
Iteration   3: 3.789 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.854 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (3.789, 3.854, 3.902), stdev = 0.058
  CI (99.9%): [2.796, 4.911] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.731 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.164 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.746 ±(99.9%) 0.007 ms/op
Iteration   1: 4.533 ±(99.9%) 0.013 ms/op
Iteration   2: 4.661 ±(99.9%) 0.011 ms/op
Iteration   3: 4.570 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.588 ±(99.9%) 1.201 ms/op [Average]
  (min, avg, max) = (4.533, 4.588, 4.661), stdev = 0.066
  CI (99.9%): [3.387, 5.789] (assumes normal distribution)


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
# Warmup Iteration   1: 12.144 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.853 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.017 ms/op
Iteration   1: 3.880 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  11.460 ms/op
                 createUser·p0.9999: 29.909 ms/op
                 createUser·p1.00:   30.474 ms/op

Iteration   2: 3.866 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.013 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  25.061 ms/op
                 createUser·p0.9999: 35.717 ms/op
                 createUser·p1.00:   38.142 ms/op

Iteration   3: 3.899 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  26.575 ms/op
                 createUser·p0.9999: 40.618 ms/op
                 createUser·p1.00:   41.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 247409
  mean =      3.882 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 236950 
    [ 5.000, 10.000) = 9900 
    [10.000, 15.000) = 241 
    [15.000, 20.000) = 62 
    [20.000, 25.000) = 44 
    [25.000, 30.000) = 111 
    [30.000, 35.000) = 17 
    [35.000, 40.000) = 68 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     23.350 ms/op
     p(99.9900) =     39.453 ms/op
     p(99.9990) =     41.191 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


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
# Warmup Iteration   1: 12.631 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.010 ms/op
Iteration   1: 3.742 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.714 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   7.315 ms/op
                 existUser·p0.999:  21.022 ms/op
                 existUser·p0.9999: 26.351 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  9.994 ms/op
                 existUser·p0.9999: 24.017 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 3.872 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  24.805 ms/op
                 existUser·p0.9999: 41.157 ms/op
                 existUser·p1.00:   41.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253324
  mean =      3.787 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 242972 
    [ 5.000, 10.000) = 9825 
    [10.000, 15.000) = 232 
    [15.000, 20.000) = 28 
    [20.000, 25.000) = 163 
    [25.000, 30.000) = 67 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     20.568 ms/op
     p(99.9900) =     40.545 ms/op
     p(99.9990) =     41.222 ms/op
     p(99.9999) =     41.222 ms/op
    p(100.0000) =     41.222 ms/op


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
# Warmup Iteration   1: 11.487 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.015 ms/op
Iteration   1: 3.971 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   8.208 ms/op
                 getUser·p0.999:  23.593 ms/op
                 getUser·p0.9999: 25.753 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   2: 3.855 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  13.092 ms/op
                 getUser·p0.9999: 27.748 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 3.856 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.794 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  29.786 ms/op
                 getUser·p0.9999: 40.348 ms/op
                 getUser·p1.00:   40.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246554
  mean =      3.893 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 236513 
    [ 5.000, 10.000) = 9384 
    [10.000, 15.000) = 313 
    [15.000, 20.000) = 63 
    [20.000, 25.000) = 99 
    [25.000, 30.000) = 107 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     23.083 ms/op
     p(99.9900) =     38.820 ms/op
     p(99.9990) =     40.667 ms/op
     p(99.9999) =     40.763 ms/op
    p(100.0000) =     40.763 ms/op


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
# Warmup Iteration   1: 13.755 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.376 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.859 ±(99.9%) 0.022 ms/op
Iteration   1: 4.596 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.751 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.960 ms/op
                 listUser·p0.999:  24.460 ms/op
                 listUser·p0.9999: 26.906 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   2: 4.495 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 24.576 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   3: 4.436 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   7.145 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 19.575 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212747
  mean =      4.508 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 189374 
    [ 5.000,  7.500) = 20489 
    [ 7.500, 10.000) = 1985 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.722 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     27.316 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.098 ± 6.411  ops/ms
ClientPb.existUser                       thrpt       3   8.551 ± 1.275  ops/ms
ClientPb.getUser                         thrpt       3   8.238 ± 3.457  ops/ms
ClientPb.listUser                        thrpt       3   6.881 ± 2.916  ops/ms
ClientPb.createUser                       avgt       3   3.833 ± 0.481   ms/op
ClientPb.existUser                        avgt       3   3.725 ± 0.790   ms/op
ClientPb.getUser                          avgt       3   3.854 ± 1.057   ms/op
ClientPb.listUser                         avgt       3   4.588 ± 1.201   ms/op
ClientPb.createUser                     sample  247409   3.882 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.509           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.350           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.453           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.812           ms/op
ClientPb.existUser                      sample  253324   3.787 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.706           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.568           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.545           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.222           ms/op
ClientPb.getUser                        sample  246554   3.893 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.393           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.083           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.820           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.763           ms/op
ClientPb.listUser                       sample  212747   4.508 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.722           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.054           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.864           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.662           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.411           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.098           ms/op
